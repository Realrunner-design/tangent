# Tangent — Marathon Passport & Map

Live site: https://realrunner-design.github.io/tangent/

Tangent tracks all 8 World Marathon Majors: entry windows, ballot deadlines, milestone reminders, finish times, a collector's passport, and quest costs. This repository holds the static site (a single `index.html` plus an `assets/` folder). There is no server and no account system — visitor progress is stored only in each visitor's own browser (localStorage).

## Notes for the owner

- **Data freshness:** the footer shows "Data last updated". Race data is re-verified daily on the Muse side; to refresh this site, replace `index.html` (and `assets/` if it changed) with the newest export and commit.
- **Paywall reality:** the paid unlock on a static public page is honor-system — the gate lives in the page code and can be bypassed by a determined visitor. There is deliberately no stronger enforcement in this build.
- **Map tiles:** tiles come from OpenStreetMap (fine for light use). Before promoting the link widely, switch to a commercial tile provider key.
- **Payments:** the buy button intentionally reads "Coming soon" until a price is chosen and a Stripe payment link is supplied.
## Rollback

To roll back, restore the previous index.html from the repo's git history: open Commits, open the earlier index.html version, then restore/re-upload it. The pre-push version is always recoverable from history.
