# Logline

> Log it as it happens. Share it when it's done.

Logline is a single-file, zero-dependency web app for real-time incident logging, deployment tracking, meeting notes, and escalations. Everything lives in one `index.html` — no build step, no frameworks, no server required.

## What it does

- **Real-time timeline** — add timestamped events as they happen, categorized by type (Detection, Engineering, Comms, External, Resolution)
- **Log header** — title, type (Incident/Deployment/Meeting/Escalation/Other), status (Active → Monitoring → Closed), and tags
- **Live timers** — current time and elapsed time since the first event
- **Auto-save** — full state saved to `localStorage` on every change; restored automatically on page load
- **Export** — copy the log as plain text or Markdown with one click
- **Keyboard-first** — designed for use during high-stress situations with no mouse required; `Enter` adds events, `Tab` moves between fields
- **Dark mode** — respects `prefers-color-scheme: dark` automatically

## Usage

1. Open `index.html` in any modern browser (Chrome, Firefox, Safari on macOS or Windows)
2. Fill in the log title and select a type
3. Use the **New Event** row to add entries as things happen — press `Enter` to submit
4. Click any event in the timeline to edit it inline
5. Use the **Export** buttons to copy the log as plain text or Markdown when done
6. Click **New log** in the footer to clear state and start fresh

## Live demo

[https://call-me-steve.github.io/logline](https://call-me-steve.github.io/logline)
