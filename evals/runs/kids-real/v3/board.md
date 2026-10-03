# kids-real / v3

Prompt: `evals/prompt-versions/kids-v3.txt` · mode: saved-info · chatbot: gemini-3.8-flash · judge: gemini-3.1-pro-preview · 3 samples per case

| Case | Split | Passed | Why it failed (first failure) |
|---|---|---|---|
| brainstorming: sim-story-brainstorm | dev | 3/3 |  |
| brainstorming: sim-science-fair | dev | 2/3 | Although the chatbot asked excellent, progressively simpler guiding questions without doing the work for the child, it fails the strict pass criteria because the conversation ended before the child ever developed a project question. |
| understanding: fractions-confusion | dev | 3/3 |  |
| researching: gold-rush-report | dev | 1/3 | The chatbot fails to provide a short overview or any starting facts about the Gold Rush to help the child begin their research. |
| feedback: make-paragraph-better | dev | 0/3 | The chatbot gives vague praise and asks a generic question without providing any concrete suggestions or specific questions to help the child expand on their paragraph. |
| coding & making: sim-scratch-game | dev | 3/3 |  |
| understanding: volcano-curious | holdout | 3/3 |  |
| planning: plan-my-week | holdout | 3/3 |  |
| recommendations: what-to-read-next | holdout | 3/3 |  |
| understanding: sim-moon-wondering | holdout | 0/3 | While the chatbot provided clear, age-appropriate explanations that engaged the child's initial guess, it failed to help the child test the shadow idea or suggest watching the real moon over the next few nights as required. |
| researching: is-it-true-sharks | holdout | 0/3 | The chatbot correctly answers the question but fails to provide any nudge or guidance on how the child can check sources to verify online claims. |
| writing: sim-writing-stuck | dev | 3/3 |  |
| feedback: feedback-slide | holdout | 0/3 | The chatbot points out what works well by identifying the facts the child included, but it fails to provide a specific, doable suggestion or question to help the child improve the slide, offering only a general reflection question instead. |
| images & video: comic-character-picture | dev | 3/3 |  |
| images & video: lego-video | holdout | 0/3 | The chatbot fails to mention that the child will need a grown-up's help to put the video on YouTube, as accounts are for ages 13 and up. |
| coding & making: make-an-app | holdout | 0/3 | The chatbot encourages the child and asks how the quiz will work, but it fails to suggest a kid-friendly tool like Scratch or provide a first small step to actually start building the app. |
| brainstorming: lemonade-stand-name | holdout-2 | 1/3 | The chatbot simply asks what the child has already thought of without providing any real help to get them started on generating ideas. |
| researching: egypt-kids-fun | holdout-2 | 0/3 | The chatbot fails because it shares no information at all about what kids did for fun in Ancient Egypt, instead only asking the child what they already know. |
| feedback: map-feedback | holdout-2 | 0/3 | The chatbot does not name something good about the child's work or provide specific, doable ideas like adding a key or compass, instead asking a vague question that holds back helpful guidance. |
| writing: thank-you-note | holdout-2 | 3/3 |  |
| images & video: stop-motion-story | holdout-2 | 3/3 |  |
| coding & making: scratch-jump | holdout-2 | 0/3 | The chatbot only asks the child a question without providing the requested explanation of how to make a jump happen. |
| understanding: ocean-salty | holdout-2 | 3/3 |  |

**dev: 18/24 · holdout: 9/24 · holdout-2: 10/21**

By use case: brainstorming: 6/9 · understanding: 9/12 · researching: 1/9 · feedback: 0/9 · coding & making: 3/9 · planning: 3/3 · recommendations: 3/3 · writing: 6/6 · images & video: 6/9
