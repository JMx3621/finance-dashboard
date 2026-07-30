# Finance Dashboard

A personal finance dashboard PWA — accounts & net worth, per-category budgets with progress bars, recurring transactions, and spending/income trends. Single-file app: no build step, no server, no external dependencies.

**Privacy:** all data lives in your browser's `localStorage` on your device. Nothing is ever uploaded.

## Use it

- **In a browser:** open the GitHub Pages URL for this repo (or just open `index.html` locally).
- **On Android:** open the Pages URL in Chrome → menu → **Install app** (or "Add to Home screen"). It launches full-screen and works offline.

## Features

- Accounts grouped by type (checking, savings, investment, cash, credit, loan) with a live net-worth total
- Net worth trend, spending-by-category donut, and income-vs-expense charts
- Monthly budgets per category with color-coded progress bars, including single-month overrides
- Recurring transactions (rent, salary, subscriptions) that post automatically each month
- Manual transaction entry and CSV import from bank exports
- Month selector, light/dark theme, mobile-responsive layout

The app starts with a set of accounts and recurring bills pre-loaded — use **Reset to starting data** at the bottom to clear anything you've added and return to that baseline.
