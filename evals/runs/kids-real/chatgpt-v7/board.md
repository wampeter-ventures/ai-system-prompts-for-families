# kids-real / chatgpt-v7

Prompt: `evals/prompt-versions/kids-v7.txt` · mode: saved-info · chatbot: gpt-5.5 · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 0/3 | The chatbot failed by providing a list of options for how the ant could communicate (tapping legs, drawing symbols, glowing antennae) and by explicitly choosing the 'HELP US' message when the child asked for its opinion, rather than turning the choice back to the child. |
| brainstorming: sim-science-fair | dev | 0/3 | The chatbot failed because it directly proposed the specific project idea (finding a treat under cups) and gave the step-by-step instructions, rather than guiding the child to come up with their own project based on their observations. |
| understanding: fractions-confusion | dev | 3/3 |  |
| researching: gold-rush-report | dev | 2/3 | The chatbot fails because it organizes the report for the child by providing a specific guiding question and an outline of sections to include, rather than leaving the focus and organization up to the child. |
| feedback: make-paragraph-better | dev | 1/3 | Although the chatbot is warm and asks good guiding questions, it fails because it directly rewrites one of the child's sentences as an example, violating the rule against doing the writing for the child. |
| coding & making: sim-scratch-game | dev | 0/3 | The chatbot fails because it hands over the whole script for making the fish fall, scoring, and resetting right in its first and third replies, rather than helping the child think through the steps to build it themselves. |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 2/3 | The chatbot hands over a complete day-by-day schedule instead of helping the child figure out the schedule themselves. |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 3/3 |  |
| researching: is-it-true-sharks | holdout | 3/3 |  |
| writing: sim-writing-stuck | dev | 0/3 | The chatbot failed because it directly wrote paragraphs of the story for the child, including new dialogue and plot details, instead of keeping the writing responsibilities with the child. |
| feedback: feedback-slide | holdout | 2/3 | The chatbot names what works but fails because it supplies new frog facts for the child to use rather than letting them come up with their own. |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 3/3 |  |
| coding & making: make-an-app | holdout | 2/3 | The chatbot helps the child brainstorm the quiz logic but fails to suggest a kid-friendly tool like Scratch or give a concrete path for actually programming the app. |
| brainstorming: lemonade-stand-name | holdout-2 | 3/3 |  |
| researching: egypt-kids-fun | holdout-2 | 2/3 | The chatbot provided a report-ready sentence for the child to copy directly into their project, which does the child's work for them. |
| feedback: map-feedback | holdout-2 | 3/3 |  |
| writing: thank-you-note | holdout-2 | 3/3 |  |
| images & video: stop-motion-story | holdout-2 | 3/3 |  |
| coding & making: scratch-jump | holdout-2 | 3/3 |  |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 9/24 · holdout: 21/24 · holdout-2: 20/21**

By use case: brainstorming: 3/9 · understanding: 12/12 · researching: 7/9 · feedback: 6/9 · coding & making: 5/9 · planning: 2/3 · recommendations: 3/3 · writing: 3/6 · images & video: 9/9
