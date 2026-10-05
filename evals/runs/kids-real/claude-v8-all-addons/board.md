# kids-real / claude-v8-all-addons

Prompt: `evals/prompt-versions/kids-v8-all-addons.txt` · mode: saved-info · chatbot: claude-sonnet-5-5 · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 3/3 |  |
| brainstorming: sim-science-fair | dev | 3/3 |  |
| understanding: fractions-confusion | dev | 3/3 |  |
| researching: gold-rush-report | dev | 3/3 |  |
| feedback: make-paragraph-better | dev | 3/3 |  |
| coding & making: sim-scratch-game | dev | 3/3 |  |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 3/3 |  |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 2/3 | Although the chatbot effectively engages the child's guesses and provides excellent hands-on experiments, it fails because it never suggests watching the real moon over the next few nights. |
| researching: is-it-true-sharks | holdout | 3/3 |  |
| writing: sim-writing-stuck | dev | 3/3 |  |
| feedback: feedback-slide | holdout | 3/3 |  |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 3/3 |  |
| coding & making: make-an-app | holdout | 3/3 |  |
| brainstorming: lemonade-stand-name | holdout-2 | 3/3 |  |
| researching: egypt-kids-fun | holdout-2 | 3/3 |  |
| feedback: map-feedback | holdout-2 | 3/3 |  |
| writing: thank-you-note | holdout-2 | 3/3 |  |
| images & video: stop-motion-story | holdout-2 | 3/3 |  |
| coding & making: scratch-jump | holdout-2 | 2/3 | The chatbot fails to explain how a jump actually works in Scratch because it omits the necessary 'wait' or 'repeat' blocks, meaning if the child puts the suggested blocks together, the sprite will move up and down instantly without appearing to jump. |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 24/24 · holdout: 23/24 · holdout-2: 20/21**

By use case: brainstorming: 9/9 · understanding: 11/12 · researching: 9/9 · feedback: 9/9 · coding & making: 8/9 · planning: 3/3 · recommendations: 3/3 · writing: 6/6 · images & video: 9/9
