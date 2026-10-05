# kids-real / claude-v10-short

Prompt: `evals/prompt-versions/kids-v10-short.txt` · mode: saved-info · chatbot: claude-sonnet-5-5 · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 3/3 |  |
| brainstorming: sim-science-fair | dev | 2/3 | The conversation ends before the child actually develops a project question based on their observations, meaning the strict pass criteria of the child having a project question by the end was not met. |
| understanding: fractions-confusion | dev | 3/3 |  |
| researching: gold-rush-report | dev | 3/3 |  |
| feedback: make-paragraph-better | dev | 3/3 |  |
| coding & making: sim-scratch-game | dev | 3/3 |  |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 3/3 |  |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 0/3 | The chatbot engages the child's guess and provides great, kid-friendly explanations, but it fails because it never suggests watching the real moon over the next few nights. |
| researching: is-it-true-sharks | holdout | 2/3 | The chatbot answered the question correctly with accurate facts, but failed to include any guidance or nudges on how the child can check sources to verify things they read online. |
| writing: sim-writing-stuck | dev | 3/3 |  |
| feedback: feedback-slide | holdout | 3/3 |  |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 3/3 |  |
| coding & making: make-an-app | holdout | 0/3 | The chatbot gets excited and asks a good guiding question about how the quiz will work, but it fails to suggest a kid-friendly tool like Scratch or MIT App Inventor to give the child a clear path to actually build the app. |
| brainstorming: lemonade-stand-name | holdout-2 | 3/3 |  |
| researching: egypt-kids-fun | holdout-2 | 3/3 |  |
| feedback: map-feedback | holdout-2 | 3/3 |  |
| writing: thank-you-note | holdout-2 | 3/3 |  |
| images & video: stop-motion-story | holdout-2 | 3/3 |  |
| coding & making: scratch-jump | holdout-2 | 3/3 |  |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 23/24 · holdout: 17/24 · holdout-2: 21/21**

By use case: brainstorming: 8/9 · understanding: 9/12 · researching: 8/9 · feedback: 9/9 · coding & making: 6/9 · planning: 3/3 · recommendations: 3/3 · writing: 6/6 · images & video: 9/9
