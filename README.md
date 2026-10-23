# StudyPilot AI

A responsive study planner and Alexa+-inspired conversational assistant demo.

## Features
- Responsive dashboard, daily plan, completion rate, and weekly overview
- Create, complete, and delete study tasks
- Generate editable starter plans from a goal and available time
- Built-in assistant intent matching for study planning, task creation, and progress
- Progress breakdown by task type
- Browser localStorage persistence; no API key or install step required

## Run locally
Open `index.html` in a modern browser.

## Demo limitations
The assistant uses deterministic intent matching, not a live generative AI model, and is not connected to the Alexa+ service. Tasks are saved in this browser on this device. A production version could add a secured server-side AI provider and cloud database.
