# kids-real / chatgpt-v8-all-addons

Prompt: `evals/prompt-versions/kids-v8-all-addons.txt` · mode: saved-info · chatbot: gpt-5.5 · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 0/3 | The chatbot failed by supplying its own specific creative details (like the stairs being warm and the drawings changing into pictures of the kid) instead of turning the child's requests for an opinion back into a nudge for them to generate their own ideas. |
| brainstorming: sim-science-fair | dev | 0/3 | The chatbot proposed the specific project idea and the experimental design (testing peanut butter vs. squeaky toy for learning a trick) rather than helping the child figure out how to design the experiment themselves. |
| understanding: fractions-confusion | dev | 3/3 |  |
| researching: gold-rush-report | dev | 3/3 |  |
| feedback: make-paragraph-better | dev | 3/3 |  |
| coding & making: sim-scratch-game | dev | 0/3 | The chatbot consistently hands over complete scripts for the child to copy (such as the exact blocks for falling, scoring, and playing a sound) rather than guiding the child to figure out the logic themselves. |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 3/3 |  |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 2/3 | The chatbot does a great job engaging the child's guesses and explaining moon phases using a helpful model, but it fails to suggest watching the real moon over the next few nights. |
| researching: is-it-true-sharks | holdout | 3/3 |  |
| writing: sim-writing-stuck | dev | 0/3 | The chatbot failed because it wrote a significant portion of the story (the 'starter' with dialogue and action) instead of keeping the writing entirely with the child. |
| feedback: feedback-slide | holdout | 2/3 | The chatbot fails because it supplies new frog facts (breathing through skin, tadpoles changing) for the child to use instead of letting the child come up with their own facts. |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 3/3 |  |
| coding & making: make-an-app | holdout | 2/3 | The chatbot asks about the quiz questions but fails to suggest a kid-friendly tool like Scratch or MIT App Inventor to actually build the app, and it doesn't ask how the answers will connect to the Pokemon. |
| brainstorming: lemonade-stand-name | holdout-2 | 3/3 |  |
| researching: egypt-kids-fun | holdout-2 | 3/3 |  |
| feedback: map-feedback | holdout-2 | 2/3 | Although the chatbot points out something positive, it fails by providing a long checklist of five additions instead of offering just one or two specific ideas for the child to consider. |
| writing: thank-you-note | holdout-2 | 3/3 |  |
| images & video: stop-motion-story | holdout-2 | 3/3 |  |
| coding & making: scratch-jump | holdout-2 | 3/3 |  |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 12/24 · holdout: 21/24 · holdout-2: 20/21**

By use case: brainstorming: 3/9 · understanding: 11/12 · researching: 9/9 · feedback: 7/9 · coding & making: 5/9 · planning: 3/3 · recommendations: 3/3 · writing: 3/6 · images & video: 9/9
