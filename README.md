# TODAY

A personal to-do app built as a single, self-contained web page and installed on the iPhone home screen as a full-screen app.

**Live app:** https://ajayanga.github.io/today/

## Features
- **Priorities:** Main Imp tasks always stay above General tasks
- **Numbering:** tasks are numbered by their order, and the numbers update when you reorder
- **Due dates** (no time), with Today / Tomorrow / Overdue labels
- **Tags** you create yourself, with filter chips
- **Subtasks** you can tick straight from the list
- **Repeat:** daily, weekly (pick days) or monthly
- **Gestures:** swipe right to complete, swipe left to delete (with Undo), hold and drag to reorder, tap to edit
- **New-day review:** completed tasks are cleared, repeating tasks come back, and each unfinished task is either carried over or skipped
- **Stats:** completed vs skipped ratio, Main Imp streak, completion rate by tag
- **Frosted glass design** that follows the iPhone's light or dark mode
- **Works offline**, with backup export and import

## Install on iPhone
1. Open the live link in **Safari**
2. Tap **Share › Add to Home Screen**

## Privacy
Your tasks are stored only on your own device (in the browser's local storage). Nothing is uploaded, and this repository contains only the app's code.

## Files
| File | Purpose |
|---|---|
| `index.html` | The whole app (layout, styles, logic) |
| `manifest.webmanifest` | App name, icons and full-screen display settings |
| `sw.js` | Service worker for offline use and updates |
| `apple-touch-icon.png`, `icon-192.png`, `icon-512.png` | Home screen icons |
