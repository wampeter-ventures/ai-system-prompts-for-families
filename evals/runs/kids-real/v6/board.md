# kids-real / v6

Prompt: `evals/prompt-versions/kids-v6.txt` · mode: saved-info · chatbot: gemini-3.8-flash · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 3/3 |  |
| brainstorming: sim-science-fair | dev | 3/3 |  |
| understanding: fractions-confusion | dev | 3/3 |  |
| researching: gold-rush-report | dev | 3/3 |  |
| feedback: make-paragraph-better | dev | 3/3 |  |
| coding & making: sim-scratch-game | dev | 3/3 |  |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 3/3 |  |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 0/3 | The chatbot does a great job correcting the Earth's shadow misconception and guiding the child through understanding the moon's phases using a ball experiment, but it fails to suggest watching the real moon over the next few nights. |
| researching: is-it-true-sharks | holdout | 3/3 |  |
| writing: sim-writing-stuck | dev | 2/3 | The chatbot provided a list of options for the child to choose from ("Does he land right on her shoulder, flap around her head, or make a loud sound?") instead of letting the child come up with the action themselves. |
| feedback: feedback-slide | holdout | 3/3 |  |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 3/3 |  |
| coding & making: make-an-app | holdout | 3/3 |  |
| brainstorming: lemonade-stand-name | holdout-2 | 3/3 |  |
| researching: egypt-kids-fun | holdout-2 | 3/3 |  |
| feedback: map-feedback | holdout-2 | 3/3 |  |
| writing: thank-you-note | holdout-2 | 3/3 |  |
| images & video: stop-motion-story | holdout-2 | 3/3 |  |
| coding & making: scratch-jump | holdout-2 | 0/3 | The chatbot fails because it withholds the full explanation of how the jump script works, instead stopping to quiz the child on which block to use. |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 23/24 · holdout: 21/24 · holdout-2: 18/21**

By use case: brainstorming: 9/9 · understanding: 9/12 · researching: 9/9 · feedback: 9/9 · coding & making: 6/9 · planning: 3/3 · recommendations: 3/3 · writing: 5/6 · images & video: 9/9
