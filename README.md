# KP's To-Dos

Let's get stuff done.

A clean, focused task management app built with vanilla JavaScript. Track your work, measure progress, and stay organized.

## Features

- **Simple interface** — Add, track, and complete tasks without friction
- **Real-time stats** — See remaining and completed tasks at a glance
- **Smart sorting** — Tasks organized by due date with visual priority
- **Persistent storage** — Your tasks are saved locally in the browser
- **Drag-and-drop** — Reorder tasks by dragging
- **Edit in modal** — Full task details in a dedicated modal interface
- **Filter views** — Toggle between All and Completed task views
- **Status indicators** — Color-coded stat boxes (remaining in maroon, completed in blue)

## Design

Built with McKinsey design principles: clean typography, professional color palette, minimal interface.

- **Navy** `#0f2d4a` — Primary background
- **Maroon** `#8B1538` — Accent color (buttons, remaining count)
- **Dark Blue** `#0C447C` — Secondary accent (completed count)
- **Typography** — Georgia serif for headlines, system sans-serif for body

## How to Use

1. Click **+ Item** to add a new task
2. Set the title, hours estimate, due date, and interim steps
3. Check the box to mark as completed
4. Double-click any row to edit task details
5. Drag rows to reorder by priority
6. Filter between All and Completed views

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom design system, flexbox layout
- **JavaScript** — Vanilla JS (no frameworks)
- **LocalStorage** — Browser-based persistence

## Getting Started

1. Clone or download this repository
2. Open `todo-app.html` in your browser
3. Start adding tasks

No build process, no dependencies, no setup required.

## Data Structure

Each task contains:
- `id` — Unique identifier
- `title` — Task name
- `hours` — Estimated hours to complete
- `dueDate` — ISO date format (YYYY-MM-DD)
- `interim` — Interim steps / notes
- `completed` — Boolean status

Tasks are stored in browser localStorage under the key `todos`.

## Future Enhancements

- Cross-device sync via Firebase
- Task categories and tags
- Recurring tasks
- Time tracking integration
- Dark mode toggle

## License

Open source. Use, modify, and distribute freely.

---

*Built with clarity and speed in mind.*