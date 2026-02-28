# H1 2026 Conference Budget Dashboard

Live dashboard pulling data from Google Sheets, hosted on GitHub Pages.

**Live URL:** https://jonah-sdm.github.io/conference-dashboard

## How to update data

1. Open the [Google Sheet](https://docs.google.com/spreadsheets/d/1onIlhT4X2ghUxlpi7FXKFUTxiRb6D-RqY5PBMPF7yI4)
2. Edit any numbers in the `📋 Conferences` or `💸 Expenses` tabs
3. Anyone viewing the dashboard just hits **↻ Refresh** in the top right to see updated numbers

## How to update the dashboard design

1. Edit `index.html`
2. Commit and push to `main`
3. GitHub Pages auto-deploys in ~60 seconds

## Sheet structure

- **📋 Conferences** — one row per conference. Update `Total Actual` after each event.
- **💸 Expenses** — one row per person per category per conference. Update `Actual Amount` after each trip.
- **📊 Summary** — auto-calculated, do not edit.
