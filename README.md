# Spending

Bare-bones monthly spending tracker for iPhone (installable web app, dot-matrix look).

- Enter item type + cost (date defaults to today). Each item gets a dot-matrix icon picked from its type.
- Shows how much is left of the month's budget, days left and a per-day allowance. Tap BUDGET to change it.
- ‹ › to look at past months. × to delete an entry.
- Data is stored only on the device (localStorage); nothing is sent anywhere. Currency symbol: `CURRENCY` at the top of the script in `index.html`.
- Icon keywords live in `RULES` in `index.html`; unmatched items show their first letter.

## Install on iPhone

Open the GitHub Pages URL in **Safari** → Share → **Add to Home Screen**, then always launch it from the home screen icon (full-screen, works offline).

## Updating

Edit, commit and push. The app checks the network first, so the next launch while online picks up the change.
