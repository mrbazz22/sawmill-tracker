# Sawmill Tracker

A single-page mobile web app for tracking sawmill lumber cuts. Save it to your iPhone home screen and use it like a native app.

## Features

- **Cut List** — All 4 phases (Back Deck → Lean-Tos → Main Barn → Greenhouse) with per-piece status tracking
- **My Logs** — Custom log entries for pieces you cut outside the list
- **Export** — Copy a text summary to paste into Messages, Notes, etc.
- **LocalStorage** — Data persists on your phone even when offline
- **Dark mode** — Easy on the eyes outdoors
- **Big tap targets** — Works with sawdust on your hands

## Save to iPhone Home Screen

1. Open `index.html` in Safari (via iCloud Drive, AirDrop, or local web server)
2. Tap the **Share** button (square with arrow)
3. Scroll down and tap **"Add to Home Screen"**
4. Name it "Sawmill" and tap **Add**

Now it opens full-screen like a real app, no browser chrome.

## How to Use

### Track Cuts
- Tap the **+** button to log a custom cut (date, log #, size, project, notes)
- In the Cut List tab, tap any piece's status button to cycle: Not Cut → Cut → Drying → Ready
- Check marks appear automatically when a piece hits "Ready"

### View Progress
- Top stats bar shows total / cut / drying / ready counts across all phases
- Each phase shows its own ready/total count

### Export
- Go to the **Export** tab
- Tap **Copy to Clipboard**
- Paste into iMessage to Max, Notes, or anywhere

## Backing Up Your Data

Everything lives in your phone's LocalStorage. To back up:

1. Go to **Export** tab
2. Copy the text
3. Paste into Apple Notes or a text file in iCloud Drive

To restore: Not yet supported automatically — paste your backup text into a note and re-enter manually if needed.

## Files

- `index.html` — The whole app (self-contained, no network needed after first load)
- `README.md` — This file

## Requirements

- Modern iPhone with iOS 14+
- Safari (for "Add to Home Screen")
- No internet required after first load

---
*Created 2026-11-21 for Jeff's sawmill tracking needs.*
