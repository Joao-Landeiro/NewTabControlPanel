# Control Panel

A personal productivity dashboard with timers, task management, quick links, and activity tracking.

## Features

### Timer
- 6 preset timers (5, 15, 30, 45, 60 minutes + custom)
- Color-coded timer buttons
- Click to start, click again to pause, click paused to reset
- Activity tracking matrix showing last 24 completed timers
- Each timer duration has a unique color in the activity log

### Quick Tasks
- Random task picker
- Add/remove tasks via config modal
- Task list management

### Quick Links
- Grid of clickable link buttons
- Manage links through config modal
- Open in new tab

### Projects
- Grid of project link buttons
- Separate from quick links for better organization
- Manage through config modal

### Notes
- CodeMirror editor with Dracula theme
- Auto-saves to localStorage
- JetBrains Mono font

### Trello Integration
- Embedded Trello board iframe

## Design
- Dark theme inspired by GitHub Dark
- JetBrains Mono font throughout
- Grid-based layout for timers, links, and projects
- Minimalist, rounded corners

## Tech Stack
- Pure HTML, CSS, JavaScript
- CodeMirror for notes
- localStorage for persistence
- No build process - just open index.html

## Usage

Simply open `index.html` in a web browser. All data is stored locally in your browser's localStorage.

