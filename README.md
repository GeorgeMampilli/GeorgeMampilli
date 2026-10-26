# Task Notepad

A notepad for tracking job applications, with two views you switch between from the bar on the left:

- **Board**: a Kanban board with four columns: **Reverts**, **Interview Round 1**, **Interview Round 2** and **Rejections**
- **List**: every task in one checklist, with All / Active / Done filters

Both views show the same tasks. It's one HTML file: open `index.html` in any browser.

## Features

- Add an application or task with notes, a priority (low / medium / high), an optional due date, and the column it belongs in
- On the board, move cards by dragging them (mouse or trackpad) or with the **Move to** menu on each card
- Tick tasks done in either view, edit them in place, or delete them (with a Delete / Keep check first); **Clear completed** removes ticked tasks
- Search and sort by newest, due date, or priority in both views
- Highlights overdue tasks and shows counts at the top
- On phones the board's columns sit side by side and you swipe between them, or tap a column name to jump to it
- Remembers which view you used last
- Light and dark themes
- Export your tasks to a JSON file and import them back (handy for backups or moving to another device)

Tasks saved by earlier versions carry over into the **Reverts** column, and finished ones stay ticked.

## Install it as an app

The notepad is an installable web app: it gets its own icon, opens full screen, and works offline.

1. Open https://georgemampilli.github.io/GeorgeMampilli/ in Chrome.
2. Tap the **⋮** menu, then **Add to home screen** → **Install** (on a computer, click the install icon in the address bar).

Installed, it keeps tasks on that device. Use **Export** now and then to back them up.

## Where data is stored

Opened as a file, the notepad saves tasks in your browser's `localStorage`, so they stay on that browser and device. Use **Export** to back them up.

The same page can also be published as a claude.ai artifact, where it saves tasks to your claude.ai account instead so they follow you across devices.

Fonts load from Google Fonts. Without an internet connection the page falls back to your system fonts and still works.
