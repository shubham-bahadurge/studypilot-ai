# StudyPilot AI

StudyPilot AI is a lightweight, responsive study planner with an **Alexa+-inspired conversational web demo**. It helps students plan study blocks, manage tasks, run focus sessions, track progress, and review flashcards.

## Features

- Responsive dashboard and mobile navigation
- Create, complete, delete, search, and filter study tasks
- Goal-based editable starter study plans
- Focus timer with start, pause, reset, and task-duration shortcut
- Progress analytics by task type and across all tasks
- Recall Lab flashcards with reveal-before-rating and spaced review intervals (1, 3, and 7 days)
- JSON backup and restore for study tasks
- Conversational study assistant that can add tasks, create a starter plan, and report progress
- Optional browser voice input (when the browser supports SpeechRecognition and microphone permission is granted)
- Optional spoken assistant replies using browser speech synthesis

## Run locally

1. Clone or download this repository.
2. Open `index.html` in a modern browser.
3. Open **Assistant** and try a prompt such as:
   - `Plan 2 hours for revision`
   - `Add a 30 minute Maths revision task`
   - `What should I study next?`
   - `Show my progress`
4. Try **Voice** if your browser supports speech recognition. Enable **Read replies** to hear assistant responses.

No package installation, API key, or backend is required for this static demo.

## Alexa+ track scope

This project demonstrates an **Alexa+-inspired experience in a web app**; it is not connected to the actual Alexa+ service and does not implement an Alexa+ Agent Skill or MCP server. The assistant uses built-in intent matching and local task actions rather than a live generative AI model. Browser speech features depend on browser support and user microphone permission.

## Data and privacy

Study tasks and flashcards are stored in the browser's `localStorage` on the current device and browser. They are not automatically synced between devices. Use **Backup** to download a JSON copy of tasks and **Restore** to import them. Keep backup files private because they contain your task details. Voice input, when used, is provided by the browser's speech-recognition implementation; behavior and processing depend on that browser.

## Hackathon change summary

The study-planning experience was extended with a conversational assistant workflow for creating study plans, adding tasks, and checking progress. Voice input and spoken replies were added as optional browser capabilities to make the interaction more assistant-like. The project remains a clearly labeled simulation and does not claim a real Alexa+ integration.

## License

This project is available under the MIT License. See [LICENSE](LICENSE).
