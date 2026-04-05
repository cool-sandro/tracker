# HOURS — Project Time Tracker

A sleek, minimal project time tracking web app built with vanilla JavaScript. Track hours spent on projects with an aesthetic cyberpunk-inspired interface.

![Version](https://img.shields.io/badge/version-live-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Features

✨ **Minimal & Fast** — Pure JavaScript, no frameworks or bloat  
⏱️ **Easy Logging** — Quick add, increment by preset amounts, or log custom hours  
📊 **Visual Charts** — Weekly and monthly trend visualization  
🎨 **Customizable** — Color-coded projects with multiple background themes  
💾 **Local Storage** — All data persists in your browser  
🎭 **Theme Options** — Star Wars, Matrix, Kill Bill, Hello Kitty, or plain dark  
📤 **Export/Import** — Backup and restore your data as JSON or CSV  

## Usage

1. **Add a Project** — Type a project name and press Enter
2. **Log Hours** — Use the preset buttons (0.5h, 1h, etc.) or enter a custom amount
3. **View Charts** — Toggle between weekly and monthly views
4. **Customize** — Change project colors, pick a background theme, export data
5. **Delete Projects** — Click the trash icon (confirm the action)

## Installation

Simply open `index.html` in your browser. No server or build step required.

Optionally, host it on GitHub Pages or any static hosting service.

## Data Storage

All project data is stored in your browser's `localStorage`:
- **Key**: `hours_projects_v1`
- **Format**: JSON array of project objects

You can export your data anytime using the export button.

## License

MIT License — see [LICENSE](LICENSE) for details.

## Live Demo

[Open HOURS](https://cool-sandro.github.io/tracker) on GitHub Pages
