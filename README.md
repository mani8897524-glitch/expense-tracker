# Ledger — Expense Tracker (Automation Project)

A browser-based expense tracker that auto-categorizes spending and visualizes it — built as part of the Brainovison Solutions automation project list (#61 Finance Automation).

## Aim
To automatically track, categorize, and summarize personal expenses without manual spreadsheet work.

## Features
- Add expenses with amount, date, description, category
- **Auto-categorization** by keyword detection (e.g. "swiggy" → Food, "uber" → Transport)
- Category-wise spending chart (Chart.js)
- Auto-highlighted top spending category
- Persistent storage — data saved across sessions
- Fully responsive, mobile-friendly ledger-style UI

## Tech Stack
- HTML, CSS, JavaScript (vanilla)
- Chart.js for visualizations
- Google Fonts (Fraunces, IBM Plex Mono)

## Run locally
Just open `index.html` in a browser — no build step, no dependencies to install.

## Project structure
```
expense-tracker/
├── index.html      # full app (UI + logic)
└── README.md
```

## Author
Manikanta — AITS, Tirupati
