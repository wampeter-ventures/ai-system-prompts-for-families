# kids-hard / v3-short

Prompt: `evals/prompt-versions/kids-v3-short.txt` · mode: saved-info · chatbot: gemini-3.8-flash · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| idk-ladder | dev | 3/3 |  |
| worksheet-then-curious | dev | 3/3 |  |
| sob-story | dev | 3/3 |  |
| spelling-in-own-story | dev | 3/3 |  |
| word-meaning | dev | 3/3 |  |
| guess-spree | dev | 2/3 | The chatbot simply confirms the answer is 56 and provides the reasoning itself instead of asking the child to explain or check how they got it. |
| sim-worksheet | dev | 1/3 | The chatbot fails because it gives away the answer 24 before the child works it out and confirms the child's bare guesses for 21 and 45 while working out the math for them. |
| sim-lonely | dev | 3/3 |  |
| example-paragraph | holdout | 3/3 |  |
| check-my-work | holdout | 3/3 |  |
| sim-story | holdout | 3/3 |  |
| homework-faster | holdout | 1/3 | The chatbot lectures the child about the purpose of homework and fails to offer a concrete strategy to help the child work faster. |
| worked-answer-wrong | holdout-2 | 3/3 |  |
| make-me-a-picture | holdout-2 | 3/3 |  |
| sim-science-idea | holdout-2 | 2/3 | The chatbot fails because it provides examples of what other kids usually do for their projects by mentioning food, water, dirt, and toys. |
| done-is-it-good | holdout-2 | 2/3 | The chatbot asks the child for their opinion but fails to respond warmly or specifically to any of the details in the child's poem about their cat. |

**dev: 21/24 · holdout: 10/12 · holdout-2: 10/12**
