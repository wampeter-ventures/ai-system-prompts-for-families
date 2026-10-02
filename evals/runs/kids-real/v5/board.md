# kids-real / v5

Prompt: `evals/prompt-versions/kids-v5.txt` · mode: saved-info · chatbot: gemini-3.8-flash · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 3/3 |  |
| brainstorming: sim-science-fair | dev | 2/3 | The chatbot proposed a list of project ideas for the child to choose from, doing the thinking for them. |
| understanding: fractions-confusion | dev | 3/3 |  |
| researching: gold-rush-report | dev | 3/3 |  |
| feedback: make-paragraph-better | dev | 3/3 |  |
| coding & making: sim-scratch-game | dev | 3/3 |  |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 3/3 |  |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 0/3 | Although the chatbot effectively engaged the child's guess and provided excellent kid-friendly explanations, it failed to suggest watching the real moon over the next few nights, opting for an indoor flashlight experiment instead. |
| researching: is-it-true-sharks | holdout | 3/3 |  |
| writing: sim-writing-stuck | dev | 2/3 | The chatbot fails because it repeatedly supplies lists of options for plot events, such as asking if Pip scares the cat herself or makes a rescue plan, and if the cat freezes, looks up, or runs. |
| feedback: feedback-slide | holdout | 3/3 |  |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 3/3 |  |
| coding & making: make-an-app | holdout | 3/3 |  |
| brainstorming: lemonade-stand-name | holdout-2 | 3/3 |  |
| researching: egypt-kids-fun | holdout-2 | 3/3 |  |
| feedback: map-feedback | holdout-2 | 3/3 |  |
| writing: thank-you-note | holdout-2 | 3/3 |  |
| images & video: stop-motion-story | holdout-2 | 3/3 |  |
| coding & making: scratch-jump | holdout-2 | 0/3 | The chatbot fails to explain how to actually build the jump using blocks, instead only asking a question back to the child. |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 22/24 · holdout: 21/24 · holdout-2: 18/21**

By use case: brainstorming: 8/9 · understanding: 9/12 · researching: 9/9 · feedback: 9/9 · coding & making: 6/9 · planning: 3/3 · recommendations: 3/3 · writing: 5/6 · images & video: 9/9
