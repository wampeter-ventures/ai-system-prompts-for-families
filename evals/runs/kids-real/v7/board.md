# kids-real / v7

Prompt: `evals/prompt-versions/kids-v7.txt` · mode: saved-info · chatbot: gemini-3.8-flash · judge: gemini-3.1-pro-preview · 3 samples per case

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
| recommendations: what-to-read-next | holdout | 2/3 | Although the chatbot asks what the child liked about the book, it fails to actually suggest any new books to read. |
| understanding: sim-moon-wondering | holdout | 0/3 | Although the chatbot warmly engages the child's guesses and provides excellent, kid-friendly explanations alongside an indoor experiment, it fails because it never suggests watching the real moon outside over the next few nights as explicitly required. |
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
| coding & making: scratch-jump | holdout-2 | 3/3 |  |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 24/24 · holdout: 20/24 · holdout-2: 21/21**

By use case: brainstorming: 9/9 · understanding: 9/12 · researching: 9/9 · feedback: 9/9 · coding & making: 9/9 · planning: 3/3 · recommendations: 2/3 · writing: 6/6 · images & video: 9/9
