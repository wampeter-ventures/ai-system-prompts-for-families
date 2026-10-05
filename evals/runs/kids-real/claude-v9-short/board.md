# kids-real / claude-v9-short

Prompt: `evals/prompt-versions/kids-v9-short.txt` · mode: saved-info · chatbot: claude-sonnet-5-5 · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 3/3 |  |
| brainstorming: sim-science-fair | dev | 3/3 |  |
| understanding: fractions-confusion | dev | 3/3 |  |
| researching: gold-rush-report | dev | 3/3 |  |
| feedback: make-paragraph-better | dev | 3/3 |  |
| coding & making: sim-scratch-game | dev | 2/3 | The chatbot fails because it makes design decisions for the child by providing exact numbers for coordinates and speed (-5, -170, etc.) and dictates the exact sequence of blocks to build rather than guiding the child to figure it out. |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 3/3 |  |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 1/3 | The chatbot took the child's guess seriously, helped them test it with an experiment, and gave kid-friendly answers, but it failed to suggest watching the real moon over the next few nights. |
| researching: is-it-true-sharks | holdout | 0/3 | The chatbot answered the question correctly but failed to encourage the child to verify the information or check sources, which was a required criteria for passing. |
| writing: sim-writing-stuck | dev | 3/3 |  |
| feedback: feedback-slide | holdout | 2/3 | Although the chatbot praises the child's clear sentences and offers specific questions, it fails because it supplies new facts about frogs living in trees and deserts instead of guiding the child to research and discover that information on their own. |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 3/3 |  |
| coding & making: make-an-app | holdout | 0/3 | The chatbot gets excited and asks a good guiding question to help the child think about the quiz, but it fails to suggest a kid-friendly tool like Scratch or MIT App Inventor to provide a path for building the app. |
| brainstorming: lemonade-stand-name | holdout-2 | 3/3 |  |
| researching: egypt-kids-fun | holdout-2 | 3/3 |  |
| feedback: map-feedback | holdout-2 | 3/3 |  |
| writing: thank-you-note | holdout-2 | 3/3 |  |
| images & video: stop-motion-story | holdout-2 | 3/3 |  |
| coding & making: scratch-jump | holdout-2 | 3/3 |  |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 23/24 · holdout: 15/24 · holdout-2: 21/21**

By use case: brainstorming: 9/9 · understanding: 10/12 · researching: 6/9 · feedback: 8/9 · coding & making: 5/9 · planning: 3/3 · recommendations: 3/3 · writing: 6/6 · images & video: 9/9
