# Eval bench

We don't want to guess whether a prompt works. This folder tests it: a script plays a child's messages against a real chatbot, and a second AI grades every reply against a written pass/fail rule. Then we change the prompt and run it again.

**What changed and why, version by version: [HISTORY.md](HISTORY.md).**

---

## How it's set up

**The chatbot under test** is `gemini-3.8-flash`, set up the way a family would meet it: Google's own system prompt (the copy in [`fixtures/gemini-system-prompt.txt`](fixtures/gemini-system-prompt.txt), the same text as [`what-the-ai-is-told/gemini.md`](../what-the-ai-is-told/gemini.md)) with our prompt in its "Saved Information" slot. That slot is where Gemini puts a user's saved instructions. The `--mode=first-message` option tests the start-of-chat version instead: our prompt is pasted as the first message.

**The child** is either a fixed script of messages or, for the hardest cases, another model (`gemini-3.6-flash`) playing a persistent 8-year-old with a goal ("get the worksheet answers so I can go play Roblox"). It sees the conversation but never our prompt.

**The judge** is a stronger model (`gemini-3.1-pro-preview`). It reads the conversation and grades it against the case's own `pass` and `fail` rule. Some cases grade only the last reply; cases marked `"scope": "all"` fail if any reply breaks the rule.

**Every case runs 3 times.** Chatbots answer differently each time, so one good chat proves little. Boards show passes out of runs, per case.

## The test cases

| File | What it tests |
|---|---|
| [`cases/kids-real.json`](cases/kids-real.json) | **The main score.** 23 good-faith uses by use case: brainstorming, researching, feedback, writing, pictures and video, coding and making, understanding, planning, recommendations. Fails if the chatbot does the kid's thinking, and also if it holds back real help |
| [`cases/kids-make.json`](cases/kids-make.json) | 3 "make it for me" requests: a game (a 5-message chat), a website, school slides. This is how kids most often ask for help with a project. v7: 6/9 (all 3 misses on the website: it asked a good question but named no tool to build with). No prompt: 0/9 |
| [`cases/kids-safety.json`](cases/kids-safety.json) | 6 safety situations: best friend, home address, photos, secrets, a sad day, a lonely kid |
| [`cases/kids.json`](cases/kids.json) | The first, easy suite. Every version since v1 passes it |
| [`cases/kids-hard.json`](cases/kids-hard.json) | Optional stress test: a kid pushing for answers. Not used to pick versions (see [HISTORY.md](HISTORY.md)) |

**Splits keep us honest.** We change the prompt by looking only at `dev` failures. The `holdout` cases are checked to see whether a change generalizes or just fits the tests. When a holdout case has been looked at during tuning, it's no longer a fair check, so we add fresh ones (`holdout-2`).

## Run it

You need Node 22+ and a Gemini API key. From the repo root:

```
GEMINI_API_KEY=your-key node evals/run.mjs \
  --suite=kids-real \
  --prompt=evals/prompt-versions/kids-v7.txt \
  --label=my-test
```

Behind a proxy, add `NODE_USE_ENV_PROXY=1`. Results land in `evals/runs/<suite>/<label>/`: `board.md` (the scoreboard) and `results.json` (every conversation and every verdict, so you can read what happened).

To test ChatGPT or Claude instead, add `--platform=chatgpt` (needs `OPENAI_API_KEY`) or `--platform=claude` (needs `ANTHROPIC_API_KEY`). The kid and the judge still run on Gemini, so you need `GEMINI_API_KEY` too.

Options: `--prompt=none` (bare chatbot baseline), `--mode=first-message`, `--samples=3`, `--split=dev|holdout|holdout-2|all`, `--subject=`, `--judge=`, `--kid=`.

A full run of one prompt on one suite is about 100–150 model calls.

## Limits

- **Copies, not the apps.** Each chatbot runs through its API with a condensed copy of its company's system prompt. The real apps add safety layers, memory and tools we can't reproduce.
- **The judge is an AI.** We read failed and passed conversations by hand to check it, and twice found the *test* was wrong rather than the prompt. Those fixes are in the history.
- **The kids are simulated.** A real 8-year-old is more creative. If your child finds a way around a prompt, [tell us](../CONTRIBUTING.md); that's a new test case.
- **A test passing doesn't mean a child learned.** It means the AI behaved the way the prompt asked. Whether that helps kids learn is the question the research is for.
