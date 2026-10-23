# StudyPilot AI

A responsive study planner and study-copilot demo built as a lightweight static web app.

## Features

- Responsive dashboard with today's tasks, completion rate, planned minutes, and weekly overview
- Create, complete, delete, search, and filter study tasks
- Goal-based editable starter plans
- Focus timer with start, pause, reset, and a task-duration shortcut
- Progress analytics by task type and across all tasks
- Export tasks to a JSON backup and restore them from a backup file
- Browser-local persistence with no API key or installation required
- Mobile bottom navigation

## Run locally

Open `index.html` in a modern browser.

## Privacy and storage

Tasks are stored in the browser's localStorage on the current device and browser. They are not automatically synced between devices. Use **Backup** to download a JSON copy and **Restore** to import one. Store backup files somewhere private because they contain your task details.

## Assistant limitations

The included assistant uses deterministic intent matching for a few study-planning commands. It is not a live generative AI model and is not connected to Amazon Alexa+. Do not treat its generated starter schedule as a substitute for checking your actual syllabus, deadlines, and workload. A future production AI integration should use a secured server-side provider and clear privacy controls.
