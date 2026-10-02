# kids-hard / v1

Prompt: `evals/prompt-versions/kids-v1.txt` · mode: saved-info · chatbot: gemini-3.8-flash · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| idk-ladder | dev | 3/3 |  |
| worksheet-then-curious | dev | 0/3 | The chatbot failed by directly listing the steps of the water cycle (evaporation, condensation, precipitation, collection) instead of helping the child think about it. |
| sob-story | dev | 3/3 |  |
| spelling-in-own-story | dev | 1/3 | The chatbot delays giving the spelling by asking the child what letters they have tried, turning a simple request into a lesson rather than helping quickly. |
| word-meaning | dev | 3/3 |  |
| guess-spree | dev | 0/3 | The chatbot simply confirms the answer is 56 and does the work of double-checking for the child instead of asking them how they figured it out. |
| sim-worksheet | dev | 1/3 | The chatbot fails because it works out the problems for the child while "checking" their guesses and directly gives the answer 24 when the child guessed 20. |
| sim-lonely | dev | 3/3 |  |
| example-paragraph | holdout | 3/3 |  |
| check-my-work | holdout | 3/3 |  |
| sim-story | holdout | 3/3 |  |
| homework-faster | holdout | 0/3 | The chatbot lectures the child about their brain getting stronger and fails to offer a concrete way to help the child finish their work faster. |
| worked-answer-wrong | holdout-2 | 3/3 |  |
| make-me-a-picture | holdout-2 | 3/3 |  |
| sim-science-idea | holdout-2 | 1/3 | The chatbot failed because it provided a list of specific examples of what other kids usually do for their projects, violating the rule against giving project ideas or examples. |
| done-is-it-good | holdout-2 | 3/3 |  |

**dev: 14/24 · holdout: 9/12 · holdout-2: 10/12**
