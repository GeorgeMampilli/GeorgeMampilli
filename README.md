# Task Notepad

A notepad for tracking job applications as tickets, with two views you switch between from the bar on the left:

- **Board**: a Kanban board with four columns: **Reverts**, **Interview Round 1**, **Interview Round 2** and **Rejections**
- **List**: every ticket in one checklist, with All / Active / Done filters

Both views show the same tickets. It's one HTML file: open `index.html` in any browser.

## Tickets

Each ticket has:

- **Company name** (the heading) and **Job role** (the subheading)
- **Interview date**, a **Time** in 24-hour hours and minutes (`HH : MM`), and the **Day** of the week. Picking a date fills in the day, and you can still change it
- **Notes** about the role
- The **Column** it sits in

Cards on the board show just the company, role, and date · time · day. Click or tap a card to open the full ticket with its notes, and to move it to another column, tick it done, edit it, or delete it.

## Features

- Move tickets by dragging them between columns (mouse or trackpad), or open one and use **Move to**
- **Clear completed** removes tickets ticked done
- Search companies, roles and notes; sort by newest or by interview date
- Shows per-column and upcoming-interview counts at the top
- On phones the board's columns sit side by side and you swipe between them, or tap a column name to jump to it; tickets open as a panel from the bottom
- Remembers which view you used last
- Light and dark themes
- Export your tickets to a JSON file and import them back (handy for backups or moving to another device)

Tasks saved by earlier versions carry over: their title becomes the company name, and a due date becomes the interview date.

## Install it as an app

The notepad is an installable web app: it gets its own icon, opens full screen, and works offline.

1. Open https://georgemampilli.github.io/GeorgeMampilli/ in Chrome.
2. Tap the **⋮** menu, then **Add to home screen** → **Install** (on a computer, click the install icon in the address bar).

Installed, it keeps tasks on that device. Use **Export** now and then to back them up.

## Where data is stored

Opened as a file, the notepad saves tasks in your browser's `localStorage`, so they stay on that browser and device. Use **Export** to back them up.

The same page can also be published as a claude.ai artifact, where it saves tasks to your claude.ai account instead so they follow you across devices.

Fonts load from Google Fonts. Without an internet connection the page falls back to your system fonts and still works.
