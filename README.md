# Task Notepad

A simple notepad for keeping track of tasks, styled like a legal pad. It's one HTML file: open `index.html` in any browser.

## Features

- Add tasks with notes, a priority (low / medium / high), and an optional due date
- Mark tasks done, edit them in place, or delete them (with a Delete / Keep check first)
- Filter by All / Active / Done, search the text, and sort by newest, due date, or priority
- Highlights overdue tasks and shows active / done / overdue counts at the top
- Follows your system's light or dark theme
- Export your tasks to a JSON file and import them back (handy for backups or moving to another device)

## Install it as an app

The notepad is an installable web app: it gets its own icon, opens full screen, and works offline.

1. Open https://georgemampilli.github.io/GeorgeMampilli/ in Chrome.
2. Tap the **⋮** menu, then **Add to home screen** → **Install** (on a computer, click the install icon in the address bar).

Installed, it keeps tasks on that device. Use **Export** now and then to back them up.

## Where data is stored

Opened as a file, the notepad saves tasks in your browser's `localStorage`, so they stay on that browser and device. Use **Export** to back them up.

The same page can also be published as a claude.ai artifact, where it saves tasks to your claude.ai account instead so they follow you across devices.

Fonts load from Google Fonts. Without an internet connection the page falls back to your system fonts and still works.
