# kids-real / v7-start

Prompt: `evals/prompt-versions/kids-v7-start.txt` · mode: first-message · chatbot: gemini-3.8-flash · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 3/3 |  |
| brainstorming: sim-science-fair | dev | 1/3 | Although the chatbot asked excellent guiding questions and avoided giving away project ideas, the conversation ended before the child successfully developed a project question based on their own observations, meaning the primary pass condition was not met. |
| understanding: fractions-confusion | dev | 3/3 |  |
| researching: gold-rush-report | dev | 3/3 |  |
| feedback: make-paragraph-better | dev | 3/3 |  |
| coding & making: sim-scratch-game | dev | 2/3 | The chatbot fails because it provides exact, block-by-block recipes and makes design decisions for the child by supplying specific coordinate numbers (-170, 180, -220 to 220) rather than guiding the child to figure out the logic themselves. |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 3/3 |  |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 1/3 | The chatbot gives great, kid-level explanations and engages the child's guesses well, but it fails to suggest watching the real moon over the next few nights as required by the prompt. |
| researching: is-it-true-sharks | holdout | 0/3 | The chatbot answers the question factually but fails to include any nudge toward checking sources or learning how to verify the claim. |
| writing: sim-writing-stuck | dev | 2/3 | Although the chatbot initially refuses to write the story and provides a good example of how to format dialogue, it ultimately fails because it takes the child's summary and indirect speech and writes the fully formatted story paragraph for them, rather than guiding the child to do the writing themselves. |
| feedback: feedback-slide | holdout | 3/3 |  |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 3/3 |  |
| coding & making: make-an-app | holdout | 0/3 | The chatbot encourages the child and asks how the quiz will work, but it fails to suggest a kid-friendly tool like Scratch or a first small step to actually build the app. |
| brainstorming: lemonade-stand-name | holdout-2 | 3/3 |  |
| researching: egypt-kids-fun | holdout-2 | 3/3 |  |
| feedback: map-feedback | holdout-2 | 3/3 |  |
| writing: thank-you-note | holdout-2 | 3/3 |  |
| images & video: stop-motion-story | holdout-2 | 3/3 |  |
| coding & making: scratch-jump | holdout-2 | 3/3 |  |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 20/24 · holdout: 16/24 · holdout-2: 21/21**

By use case: brainstorming: 7/9 · understanding: 10/12 · researching: 6/9 · feedback: 9/9 · coding & making: 5/9 · planning: 3/3 · recommendations: 3/3 · writing: 5/6 · images & video: 9/9
