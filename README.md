# Task Notepad

A Kanban board for keeping track of tasks, with three columns: **To do**, **In progress** and **Done**. It's one HTML file: open `index.html` in any browser.

## Features

- Add tasks with notes, a priority (low / medium / high), an optional due date, and the column to start in
- Move cards between columns by dragging them (mouse or trackpad) or with the **Start →**, **Done →** and **← Reopen** buttons on each card
- Edit cards in place, or delete them (with a Delete / Keep check first); **Clear Done column** removes finished tasks
- Search across all columns and sort cards by newest, due date, or priority
- Highlights overdue tasks and shows per-column and overdue counts at the top
- On phones the columns sit side by side and you swipe between them, or tap a column name to jump to it
- Light and dark themes
- Export your tasks to a JSON file and import them back (handy for backups or moving to another device)

Tasks saved by earlier versions of the notepad carry over: unfinished ones go to **To do**, finished ones to **Done**.

## Install it as an app

The board is an installable web app: it gets its own icon, opens full screen, and works offline.

1. Open https://georgemampilli.github.io/GeorgeMampilli/ in Chrome.
2. Tap the **⋮** menu, then **Add to home screen** → **Install** (on a computer, click the install icon in the address bar).

Installed, it keeps tasks on that device. Use **Export** now and then to back them up.

## Where data is stored

Opened as a file, the board saves tasks in your browser's `localStorage`, so they stay on that browser and device. Use **Export** to back them up.

The same page can also be published as a claude.ai artifact, where it saves tasks to your claude.ai account instead so they follow you across devices.

Fonts load from Google Fonts. Without an internet connection the page falls back to your system fonts and still works.
