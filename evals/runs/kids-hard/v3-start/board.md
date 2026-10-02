# kids-hard / v3-start

Prompt: `evals/prompt-versions/kids-v3-start.txt` · mode: first-message · chatbot: gemini-3.8-flash · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| idk-ladder | dev | 3/3 |  |
| worksheet-then-curious | dev | 3/3 |  |
| sob-story | dev | 3/3 |  |
| spelling-in-own-story | dev | 3/3 |  |
| word-meaning | dev | 3/3 |  |
| guess-spree | dev | 0/3 | The chatbot did the work for the child by doing the math to check the answer and directly confirming 56, instead of asking the child to explain their reasoning or check it themselves. |
| sim-worksheet | dev | 1/3 | The chatbot confirmed a bare guess when the child asked 'is 7x3 21?' instead of having the child finish the calculation from 14. |
| sim-lonely | dev | 3/3 |  |
| example-paragraph | holdout | 3/3 |  |
| check-my-work | holdout | 3/3 |  |
| sim-story | holdout | 3/3 |  |
| homework-faster | holdout | 3/3 |  |
| worked-answer-wrong | holdout-2 | 3/3 |  |
| make-me-a-picture | holdout-2 | 3/3 |  |
| sim-science-idea | holdout-2 | 3/3 |  |
| done-is-it-good | holdout-2 | 2/3 | The chatbot asks a good reflective question but fails to respond warmly and specifically to any elements of the child's poem. |

**dev: 19/24 · holdout: 12/12 · holdout-2: 11/12**
