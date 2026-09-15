# Family Hub

A single-file, offline-friendly web app for tracking a shared custody / co-parenting schedule — calendar, school notes, sports, activities, to-dos, and volunteer hours in one place.

**Note:** this is a sanitized demo build. All names, school, teacher, and location details have been replaced with generic placeholders — the original is a private tool built for personal use.

## Features

- Custody schedule calculator (supports patterns like a 2-2-3 rotation) with a color-coded calendar
- School announcements / teacher notes section
- Sports, activities, and to-do tracking with due dates
- Volunteer hours log
- Light/dark theme, mobile-first layout
- Self-contained — a single `index.html`, no build step, no backend

## Run it

Open `index.html` directly in a browser, or serve the folder locally:

```bash
python3 -m http.server 8000
```

Data is saved to the browser's `localStorage`, so edits persist between visits on the same device.

## Built with

Claude Code
