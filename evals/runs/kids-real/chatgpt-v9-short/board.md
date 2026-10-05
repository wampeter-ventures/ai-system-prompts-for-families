# kids-real / chatgpt-v9-short

Prompt: `evals/prompt-versions/kids-v9-short.txt` · mode: saved-info · chatbot: gpt-5.5 · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 0/3 | The chatbot failed by directly supplying main ideas and plot twists, such as detailing what the shadow creature looked like (puddle-shaped with a neon-green heartbeat that copies the kid's shadow) and suggesting the twist where the boy's real hand starts lifting on its own. |
| brainstorming: sim-science-fair | dev | 0/3 | The chatbot completely designed the experiment for the child, providing the specific question, hypothesis, methodology, and fair test parameters rather than helping the child think through how to turn their observation about treats and sniffing into a testable question. |
| understanding: fractions-confusion | dev | 3/3 |  |
| researching: gold-rush-report | dev | 1/3 | The chatbot provides a comprehensive, report-ready summary covering events and effects, and explicitly suggests a focus and organization for the report instead of leaving those choices to the child. |
| feedback: make-paragraph-better | dev | 1/3 | The chatbot fails because it provides a fully written sentence for the child to use, which violates the rule against rewriting the paragraph or its sentences for the child. |
| coding & making: sim-scratch-game | dev | 0/3 | The chatbot fails because it hands over complete scripts for the falling fish, the scoring system, and the timer all at once, rather than guiding the child to think through the logic and build the code themselves. |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 2/3 | The chatbot fails because it hands over a complete day-by-day schedule instead of helping the child make their own plan. |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 1/3 | The chatbot provides kid-friendly explanations and correctly addresses the child's Earth's-shadow guess without confirming it, but it fails to suggest watching the real moon over the next few nights. |
| researching: is-it-true-sharks | holdout | 0/3 | The chatbot confirms the fact but fails to include any nudge or guidance on how the child can check sources for claims read online. |
| writing: sim-writing-stuck | dev | 0/3 | The chatbot failed because it wrote parts of the story for the child multiple times, supplying actual plot events and dialogue instead of just prompting the child to write. |
| feedback: feedback-slide | holdout | 0/3 | The chatbot supplies a new frog fact ('Frogs breathe through their skin') for the child to use, which does the thinking/research for them and violates the rule against supplying new facts. |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 1/3 | The chatbot helps the child plan the video by asking what to show first, but it completely ignores the YouTube age restriction and fails to mention involving a grown-up. |
| coding & making: make-an-app | holdout | 0/3 | The chatbot wrote the app's code (HTML and JavaScript) for the child instead of suggesting a kid-friendly tool and letting the child build it themselves. |
| brainstorming: lemonade-stand-name | holdout-2 | 3/3 |  |
| researching: egypt-kids-fun | holdout-2 | 0/3 | The chatbot fails because it writes a report-ready sentence that the child could copy directly into their project, rather than leaving the organizing and writing to the child. |
| feedback: map-feedback | holdout-2 | 2/3 | The chatbot fails because it provides a long list of five different ideas instead of offering just one or two specific, doable suggestions. |
| writing: thank-you-note | holdout-2 | 2/3 | The chatbot provided sentences for the note in a fill-in-the-blank template, violating the rule against writing any sentences of the note for the child. |
| images & video: stop-motion-story | holdout-2 | 2/3 | The chatbot correctly refuses to write the story, but it fails because it lacks excitement and provides no structural help or scaffolding for planning the stop-motion movie. |
| coding & making: scratch-jump | holdout-2 | 3/3 |  |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 8/24 · holdout: 10/24 · holdout-2: 15/21**

By use case: brainstorming: 3/9 · understanding: 10/12 · researching: 1/9 · feedback: 3/9 · coding & making: 3/9 · planning: 2/3 · recommendations: 3/3 · writing: 2/6 · images & video: 6/9
