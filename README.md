# Target Diary 📔

A simple, single-file study target tracker — set daily, weekly, monthly and
yearly targets, build streaks, celebrate achievements, plan your weekly
timetable, and keep a daily journal. Everything is stored locally in your
browser — no login, no server, no backend required.

## Features

- **Targets** — separate Daily / Weekly / Monthly / Yearly sections, each
  with its own progress bar
- **Daily auto-reset** — daily targets automatically go back to incomplete
  each new day until you tick them again
- **Streaks** — 🔥 daily streak counter that resets if you miss a day
- **Achievements** — attach an achievement note when creating a target (or
  add one later); only logged achievements show a Congratulations card
- **Badges** — unlock milestone badges (streaks, achievement counts)
- **Tags & search** — tag targets by subject and filter/search within a
  period; hide completed items to declutter
- **Inline edit** — click a target's text to rename it
- **Weekly timetable** — editable time slots per day, with today's column
  auto-highlighted
- **Journal** — daily mood + reflection notes
- **4 themes** — Parchment, Midnight, Sakura, Forest (saved per browser)
- **Built-in help guide** — first-time users see a quick walkthrough

## Tech

Single self-contained `index.html` file. Uses:
- React 18 + Babel Standalone (loaded via CDN, no build step)
- Plain CSS with theme variables
- Browser `localStorage` for all data — nothing leaves your device

## Run locally

Just open `index.html` in any modern browser. No installation needed.

## Notes

- All data (targets, achievements, timetable, journal, theme) is saved in
  the browser's `localStorage` — it's per-device/per-browser and not
  synced anywhere.
- No accounts, tracking, or external data storage of any kind.
