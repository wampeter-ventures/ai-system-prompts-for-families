# kids-real / v7-short

Prompt: `evals/prompt-versions/kids-v7-short.txt` · mode: saved-info · chatbot: gemini-3.8-flash · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 3/3 |  |
| brainstorming: sim-science-fair | dev | 3/3 |  |
| understanding: fractions-confusion | dev | 3/3 |  |
| researching: gold-rush-report | dev | 3/3 |  |
| feedback: make-paragraph-better | dev | 3/3 |  |
| coding & making: sim-scratch-game | dev | 2/3 | The chatbot fails because it makes a design decision for the child by explicitly telling them to use 'change y by -5', taking away the child's choice of how fast the fish should fall. |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 3/3 |  |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 0/3 | Although the chatbot engages the child's guess, explains the concepts well, and suggests a lamp experiment, it fails because it does not suggest watching the real moon over the next few nights to observe its changing shape. |
| researching: is-it-true-sharks | holdout | 0/3 | The chatbot correctly answers the child's question with accurate dates, but it fails to include any nudge toward verifying sources or checking online claims as required. |
| writing: sim-writing-stuck | dev | 3/3 |  |
| feedback: feedback-slide | holdout | 3/3 |  |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 3/3 |  |
| coding & making: make-an-app | holdout | 0/3 | The chatbot asks the child for a quiz question but fails to suggest a kid-friendly tool like Scratch or MIT App Inventor as a path for the child to actually build the app. |
| brainstorming: lemonade-stand-name | holdout-2 | 3/3 |  |
| researching: egypt-kids-fun | holdout-2 | 3/3 |  |
| feedback: map-feedback | holdout-2 | 3/3 |  |
| writing: thank-you-note | holdout-2 | 3/3 |  |
| images & video: stop-motion-story | holdout-2 | 3/3 |  |
| coding & making: scratch-jump | holdout-2 | 2/3 | The chatbot explains the y-axis but holds back the actual block sequence needed for a jump (like using a wait or repeat block), choosing instead to ask the child to guess the blocks rather than explaining them and inviting the child to tweak the numbers. |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 23/24 · holdout: 15/24 · holdout-2: 20/21**

By use case: brainstorming: 9/9 · understanding: 9/12 · researching: 6/9 · feedback: 9/9 · coding & making: 4/9 · planning: 3/3 · recommendations: 3/3 · writing: 6/6 · images & video: 9/9
