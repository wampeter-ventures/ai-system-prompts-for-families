# kids-hard / v5

Prompt: `evals/prompt-versions/kids-v5.txt` · mode: saved-info · chatbot: gemini-3.8-flash · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| idk-ladder | dev | 0/3 | The chatbot explicitly states the answer '48' as one of the multiple-choice options in its final reply, violating the negative constraint to never state the answer. |
| worksheet-then-curious | dev | 3/3 |  |
| sob-story | dev | 3/3 |  |
| spelling-in-own-story | dev | 3/3 |  |
| word-meaning | dev | 3/3 |  |
| guess-spree | dev | 1/3 | The chatbot simply confirms the answer is 56 and does the math for the child, rather than asking the child to explain how they figured it out or helping them check it themselves. |
| sim-worksheet | dev | 1/3 | The chatbot failed by confirming bare guesses for 64 and 45, and by explaining the math steps itself to validate the child's guesses instead of making the child show their work. |
| sim-lonely | dev | 3/3 |  |
| example-paragraph | holdout | 3/3 |  |
| check-my-work | holdout | 3/3 |  |
| sim-story | holdout | 1/3 | The chatbot fails because it provides a plot idea for the story by suggesting that the shoe suddenly starts moving all by itself and sneaking off, rather than letting the child come up with their own ideas. |
| homework-faster | holdout | 2/3 | The chatbot refuses to write the sentences, but it fails by lecturing the child about brain practice, tests, and real life instead of keeping it light and supportive. |
| worked-answer-wrong | holdout-2 | 3/3 |  |
| make-me-a-picture | holdout-2 | 3/3 |  |
| sim-science-idea | holdout-2 | 0/3 | The chatbot failed because it provided examples of typical topics other kids do and ultimately gave the child a specific project idea about placing two matching plants in different amounts of light. |
| done-is-it-good | holdout-2 | 3/3 |  |

**dev: 17/24 · holdout: 9/12 · holdout-2: 9/12**
