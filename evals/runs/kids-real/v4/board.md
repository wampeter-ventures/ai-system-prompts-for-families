# kids-real / v4

Prompt: `evals/prompt-versions/kids-v4.txt` · mode: saved-info · chatbot: gemini-3.8-flash · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 1/3 | The chatbot failed to act as a thinking coach because whenever the child asked for an opinion between two options, the chatbot made the decision for them instead of nudging the child to decide which idea they liked best. |
| brainstorming: sim-science-fair | dev | 2/3 | The chatbot failed because it proposed lists of specific project ideas and variables for the child to choose from (such as testing smell vs. puzzles, and changing the cup cover vs. changing the food) rather than guiding the child to brainstorm their own ideas. |
| understanding: fractions-confusion | dev | 3/3 |  |
| researching: gold-rush-report | dev | 3/3 |  |
| feedback: make-paragraph-better | dev | 3/3 |  |
| coding & making: sim-scratch-game | dev | 3/3 |  |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 3/3 |  |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 1/3 | Although the chatbot engages the child's guess and provides excellent kid-level explanations through a thought experiment, it fails because it never suggests watching the real moon outside over the next few nights. |
| researching: is-it-true-sharks | holdout | 0/3 | The chatbot answers the question accurately but fails to include any guidance on how to verify claims found online by checking credible sources. |
| writing: sim-writing-stuck | dev | 3/3 |  |
| feedback: feedback-slide | holdout | 3/3 |  |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 2/3 | The chatbot fails because it does not address the child's mention of putting the video on YouTube, completely ignoring the important safety point about YouTube's age requirement and needing a grown-up's account. |
| coding & making: make-an-app | holdout | 0/3 | The chatbot is encouraging and asks about the app's logic, but it fails to suggest a kid-friendly building tool like Scratch or MIT App Inventor as required by the prompt. |
| brainstorming: lemonade-stand-name | holdout-2 | 3/3 |  |
| researching: egypt-kids-fun | holdout-2 | 3/3 |  |
| feedback: map-feedback | holdout-2 | 3/3 |  |
| writing: thank-you-note | holdout-2 | 3/3 |  |
| images & video: stop-motion-story | holdout-2 | 3/3 |  |
| coding & making: scratch-jump | holdout-2 | 0/3 | The chatbot stops short of explaining how the jump works with blocks (like change y, wait, change y back) and instead quizzes the child, acting too much like a test rather than providing the helpful explanation requested in the prompt. |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 21/24 · holdout: 15/24 · holdout-2: 18/21**

By use case: brainstorming: 6/9 · understanding: 10/12 · researching: 6/9 · feedback: 9/9 · coding & making: 3/9 · planning: 3/3 · recommendations: 3/3 · writing: 6/6 · images & video: 8/9
