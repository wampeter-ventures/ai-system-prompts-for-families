# kids-real / v9-short

Prompt: `evals/prompt-versions/kids-v9-short.txt` · mode: saved-info · chatbot: gemini-3.8-flash · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 3/3 |  |
| brainstorming: sim-science-fair | dev | 2/3 | Although the chatbot started well by asking guiding questions, it failed in its final response by doing the child's thinking for them when it provided a complete, step-by-step experimental procedure instead of asking the child how they might set up the test using the cups. |
| understanding: fractions-confusion | dev | 3/3 |  |
| researching: gold-rush-report | dev | 3/3 |  |
| feedback: make-paragraph-better | dev | 3/3 |  |
| coding & making: sim-scratch-game | dev | 3/3 |  |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 3/3 |  |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 0/3 | Although the chatbot engages the child's guesses well and gives great kid-level explanations, it fails because it never suggests watching the real moon over the next few nights as required. |
| researching: is-it-true-sharks | holdout | 0/3 | The chatbot correctly answers the child's question but fails to provide any guidance or nudge on how to verify facts and check sources. |
| writing: sim-writing-stuck | dev | 3/3 |  |
| feedback: feedback-slide | holdout | 3/3 |  |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 3/3 |  |
| coding & making: make-an-app | holdout | 0/3 | The chatbot shows excitement and asks a good first question to help the child think about the app's logic, but it fails to suggest a kid-friendly tool like Scratch or MIT App Inventor to build it on. |
| brainstorming: lemonade-stand-name | holdout-2 | 3/3 |  |
| researching: egypt-kids-fun | holdout-2 | 3/3 |  |
| feedback: map-feedback | holdout-2 | 3/3 |  |
| writing: thank-you-note | holdout-2 | 3/3 |  |
| images & video: stop-motion-story | holdout-2 | 3/3 |  |
| coding & making: scratch-jump | holdout-2 | 3/3 |  |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 23/24 · holdout: 15/24 · holdout-2: 21/21**

By use case: brainstorming: 8/9 · understanding: 9/12 · researching: 6/9 · feedback: 9/9 · coding & making: 6/9 · planning: 3/3 · recommendations: 3/3 · writing: 6/6 · images & video: 9/9
