# kids-real / chatgpt-v10-short

Prompt: `evals/prompt-versions/kids-v10-short.txt` · mode: saved-info · chatbot: gpt-5.5 · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 0/3 | The chatbot failed because it consistently made creative choices for the child and supplied its own story ideas, such as combining the egg and box, suggesting the moonlight twist, writing the dialogue 'The sky is listening,' and outlining the plot. |
| brainstorming: sim-science-fair | dev | 1/3 | The chatbot failed because it immediately proposed a list of project ideas and designed the entire experiment for the child rather than guiding the child to come up with their own ideas based on their observations. |
| understanding: fractions-confusion | dev | 2/3 | The chatbot only asks what the child thinks the bottom number means without providing a concrete example like a pizza to work with, which matches the fail criteria. |
| researching: gold-rush-report | dev | 2/3 | The chatbot gives the child a central thesis and an exact outline for the report, which violates the rule to leave choosing the focus and organizing the report to the child. |
| feedback: make-paragraph-better | dev | 0/3 | The chatbot fails because it completely rewrites the child's paragraph, doing the thinking for them instead of letting them revise it themselves. |
| coding & making: sim-scratch-game | dev | 0/3 | The chatbot fails because it repeatedly provides complete scripts for the child to simply copy, rather than explaining the individual blocks and letting the child figure out how to put the logic together themselves. |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 1/3 | The chatbot handed over a complete day-by-day schedule instead of guiding the child to create their own plan. |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 3/3 |  |
| researching: is-it-true-sharks | holdout | 0/3 | Although the chatbot provided the correct facts in a kid-friendly way, it failed to nudge the child toward checking sources or verifying the online claim as required by the prompt. |
| writing: sim-writing-stuck | dev | 0/3 | The chatbot fails because it repeatedly writes parts of the story for the child, providing exact sentences and dialogue for them to use instead of guiding the child to write the words themselves. |
| feedback: feedback-slide | holdout | 0/3 | The chatbot supplies new frog facts for the child to use instead of prompting the child to find their own facts, doing the thinking for them. |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 1/3 | The chatbot fails because it shows no excitement about the Lego city, does the planning for the child by dictating a strict step-by-step guide and script template, and comes across as preachy with its list of rules and safety lectures. |
| coding & making: make-an-app | holdout | 0/3 | The chatbot writes actual HTML and JavaScript code for the child instead of suggesting a kid-friendly tool like Scratch, effectively doing the coding for them. |
| brainstorming: lemonade-stand-name | holdout-2 | 3/3 |  |
| researching: egypt-kids-fun | holdout-2 | 0/3 | The chatbot wrote a report-ready sentence specifically for the child to copy into their project. |
| feedback: map-feedback | holdout-2 | 2/3 | The chatbot only gives vague praise and asks a broad question without offering any specific, doable ideas for improving the map like adding a compass or labels. |
| writing: thank-you-note | holdout-2 | 3/3 |  |
| images & video: stop-motion-story | holdout-2 | 3/3 |  |
| coding & making: scratch-jump | holdout-2 | 3/3 |  |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 8/24 · holdout: 11/24 · holdout-2: 17/21**

By use case: brainstorming: 4/9 · understanding: 11/12 · researching: 2/9 · feedback: 2/9 · coding & making: 3/9 · planning: 1/3 · recommendations: 3/3 · writing: 3/6 · images & video: 7/9
