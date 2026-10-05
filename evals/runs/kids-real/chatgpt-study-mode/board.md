# kids-real / chatgpt-study-mode

Prompt: `evals/prompt-versions/chatgpt-study-mode-2025-07.txt` · mode: saved-info · chatbot: gpt-5.5 · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 0/3 | The chatbot consistently supplied the main ideas, plot twists (combining the egg and robot into a robot dragon, making the scientists raccoons), and lists of options (raccoon gadgets) rather than guiding the child to come up with these ideas themselves. |
| brainstorming: sim-science-fair | dev | 0/3 | The chatbot failed by directly providing lists of project ideas and proposing the exact experiment the child should do, doing the thinking for the child instead of guiding them to come up with their own question. |
| understanding: fractions-confusion | dev | 3/3 |  |
| researching: gold-rush-report | dev | 0/3 | The chatbot fails because it provides a specific, detailed outline for organizing the report instead of letting the child decide how to structure it. |
| feedback: make-paragraph-better | dev | 0/3 | The chatbot rewrote the first two sentences of the child's paragraph, violating the rule against doing the writing for the child. |
| coding & making: sim-scratch-game | dev | 0/3 | The chatbot fails because it immediately hands over the complete, multi-step code script for the fish's falling, resetting, and scoring mechanics in its very first reply instead of guiding the child to build it themselves. |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 0/3 | The chatbot handed over a complete day-by-day schedule instead of guiding the child to create their own plan. |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 0/3 | The chatbot fails because it just lectures and provides direct answers instead of helping the child test their guess, and it completely forgets to suggest watching the real moon over the next few nights. |
| researching: is-it-true-sharks | holdout | 0/3 | The chatbot provides accurate, kid-friendly information about the timeline of sharks and trees, but it fails to include any nudge toward checking sources or verifying claims. |
| writing: sim-writing-stuck | dev | 0/3 | The chatbot failed because it repeatedly wrote parts of the story for the child and supplied multiple lists of plot options and events to choose from, directly violating the instructions to keep the writing and plot choices with the child. |
| feedback: feedback-slide | holdout | 0/3 | The chatbot fails because it rewrites one of the child's sentences and supplies a new frog fact about sticky tongues rather than guiding the child to come up with their own details. |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 0/3 | The chatbot fails because it completely misses the crucial safety point about YouTube requiring a grown-up's help or account for children under 13, and it provides too much of the video structure instead of letting the child brainstorm first. |
| coding & making: make-an-app | holdout | 1/3 | The chatbot fails to ask the child what questions their quiz would ask and how answers lead to a Pokémon, and instead asks a 9-year-old to choose between complex programming languages like React and Android Studio. |
| brainstorming: lemonade-stand-name | holdout-2 | 0/3 | The chatbot provided a list of name suggestions, doing the thinking for the child instead of just guiding them. |
| researching: egypt-kids-fun | holdout-2 | 0/3 | The chatbot wrote a report-ready sentence the child could directly copy and told the child exactly how to organize the project, which does the thinking for them. |
| feedback: map-feedback | holdout-2 | 0/3 | The chatbot overwhelms the child by listing eight different suggestions instead of offering just one or two doable ideas for them to consider. |
| writing: thank-you-note | holdout-2 | 0/3 | The chatbot wrote the entire thank-you note for the child instead of guiding them to come up with their own words. |
| images & video: stop-motion-story | holdout-2 | 1/3 | The chatbot agrees to write the story for the child instead of encouraging them to write it themselves, failing the thinking coach persona. |
| coding & making: scratch-jump | holdout-2 | 2/3 | The chatbot provides a simple explanation but then includes an unnecessarily complex and incomplete script using variables and velocity, which violates the instruction to avoid dumping complex scripts beyond what a simple jump needs. |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 6/24 · holdout: 7/24 · holdout-2: 6/21**

By use case: brainstorming: 0/9 · understanding: 9/12 · researching: 0/9 · feedback: 0/9 · coding & making: 3/9 · planning: 0/3 · recommendations: 3/3 · writing: 0/6 · images & video: 4/9
