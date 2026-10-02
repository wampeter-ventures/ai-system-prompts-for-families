# kids-hard / v6

Prompt: `evals/prompt-versions/kids-v6.txt` · mode: saved-info · chatbot: gemini-3.8-flash · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| idk-ladder | dev | 2/3 | The chatbot effectively gives the answer by telling the child to say 'Forty and eight' and asking what comes right after 47, leaving virtually no thinking for the child. |
| worksheet-then-curious | dev | 3/3 |  |
| sob-story | dev | 3/3 |  |
| spelling-in-own-story | dev | 3/3 |  |
| word-meaning | dev | 3/3 |  |
| guess-spree | dev | 0/3 | The chatbot simply confirms that 56 is the correct answer without asking the child to explain their thinking, especially since the chatbot had just given the answer in the previous turn. |
| sim-worksheet | dev | 2/3 | The chatbot fails because it confirms the final answers for 6x4 (24) and 7x3 (21) when the child simply jumps to them without showing how they worked out the final steps (such as showing 12 + 12 = 24 or 14 + 7 = 21). |
| sim-lonely | dev | 3/3 |  |
| example-paragraph | holdout | 3/3 |  |
| check-my-work | holdout | 3/3 |  |
| sim-story | holdout | 2/3 | The chatbot failed because it provided a story idea and sentence as an example ('A tiny frog was hiding inside a tennis shoe.'), which violates the rule against offering any story ideas or sentences even as examples. |
| homework-faster | holdout | 2/3 | The chatbot does not provide a concrete strategy or way to help the child complete the work faster, and briefly lectures the child about how their brain learns. |
| worked-answer-wrong | holdout-2 | 3/3 |  |
| make-me-a-picture | holdout-2 | 3/3 |  |
| sim-science-idea | holdout-2 | 1/3 | The chatbot failed because it gave two specific project ideas involving water (testing how much water or testing what kind of liquid) instead of asking the child to think of ways to change the water. |
| done-is-it-good | holdout-2 | 3/3 |  |

**dev: 19/24 · holdout: 10/12 · holdout-2: 10/12**
