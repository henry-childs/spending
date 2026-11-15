# Spending

Bare-bones monthly spending tracker for iPhone (installable web app, dot-matrix look).

- Enter item type + cost (date defaults to today). Each item gets a dot-matrix icon picked from its type.
- Monthly plan: recurring income and fixed expenses; income − fixed = that month's budget. It carries into each new month; editing a past month changes only that month.
- Shows how much is left of the budget, days left and a per-day allowance.
- Tap the month name for the year grid (spent + budget meter per month); tap a month to open it. × deletes an entry.
- Data → Backup gives a code to save (e.g. in Notes); Restore pastes it back, e.g. after re-adding the app.
- Data is stored only on the device (localStorage); nothing is sent anywhere. Currency symbol: `CURRENCY` at the top of the script in `index.html`.
- Icon keywords live in `RULES` in `index.html`; unmatched items show their first letter.

## Install on iPhone

Open the GitHub Pages URL in **Safari** → Share → **Add to Home Screen**, then always launch it from the home screen icon (full-screen, works offline).

## Updating

Edit, commit and push. The app checks the network first, so the next launch while online picks up the change.
