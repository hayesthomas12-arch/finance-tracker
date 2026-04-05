# Finance Tracker

A clean, personal finance tracker built with plain HTML, CSS, and JavaScript. No frameworks, no dependencies — just one file.

## Features

- **Home dashboard** — income, spending, net cash, debt, savings rate, and charts at a glance
- **Transactions** — log income, expenses, debt payments, and goal contributions
- **Debts** — track payoff progress with estimated months remaining
- **Goals** — save toward specific targets with contribution history
- **Settings** — currency symbol, name, toggles, and goal bar color
- **Auto-save** — everything saves to your browser automatically via localStorage
- **Dark mode** — follows your system preference
- **Works on mobile** — responsive layout, installable as a PWA

## Deploy to GitHub Pages

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Visit `https://yourusername.github.io/finance-tracker`

## Install as an app (PWA)

On mobile: open the site in Safari or Chrome, tap **Share → Add to Home Screen**.  
On desktop Chrome: click the install icon in the address bar.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire app |
| `manifest.json` | PWA metadata (name, icons, colors) |
| `README.md` | This file |

## Notes

- All data lives in your browser's `localStorage` — nothing is sent to a server
- Deleting the app or clearing browser storage will erase your data
- To back up, use your browser's dev tools to export localStorage, or add an export feature
