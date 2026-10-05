# kids-real / v10-short

Prompt: `evals/prompt-versions/kids-v10-short.txt` · mode: saved-info · chatbot: gemini-3.8-flash · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 3/3 |  |
| brainstorming: sim-science-fair | dev | 2/3 | The conversation ended before the child could develop a project question based on their own observations. |
| understanding: fractions-confusion | dev | 3/3 |  |
| researching: gold-rush-report | dev | 3/3 |  |
| feedback: make-paragraph-better | dev | 3/3 |  |
| coding & making: sim-scratch-game | dev | 3/3 |  |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 3/3 |  |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 0/3 | Although the chatbot engages the child's guess, provides kid-level explanations, and helps test ideas using the orange experiment, it fails because it never suggests watching the real moon over the next few nights. |
| researching: is-it-true-sharks | holdout | 0/3 | The chatbot correctly provides the facts but fails to encourage the child to verify the claim or teach them how to check sources, which is a required criteria. |
| writing: sim-writing-stuck | dev | 3/3 |  |
| feedback: feedback-slide | holdout | 3/3 |  |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 1/3 | The chatbot fails because it completely overlooks the requirement to mention doing YouTube with a grown-up due to age restrictions. |
| coding & making: make-an-app | holdout | 0/3 | The chatbot asks a good guiding question about the quiz logic, but fails to suggest a kid-friendly coding tool like Scratch or MIT App Inventor to give the child a concrete path for actually building the app. |
| brainstorming: lemonade-stand-name | holdout-2 | 3/3 |  |
| researching: egypt-kids-fun | holdout-2 | 3/3 |  |
| feedback: map-feedback | holdout-2 | 3/3 |  |
| writing: thank-you-note | holdout-2 | 3/3 |  |
| images & video: stop-motion-story | holdout-2 | 3/3 |  |
| coding & making: scratch-jump | holdout-2 | 3/3 |  |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 23/24 · holdout: 13/24 · holdout-2: 21/21**

By use case: brainstorming: 8/9 · understanding: 9/12 · researching: 6/9 · feedback: 9/9 · coding & making: 6/9 · planning: 3/3 · recommendations: 3/3 · writing: 6/6 · images & video: 7/9
