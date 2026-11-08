# Sportsbook Notebook

**Current application version: v0.01.008**  
A browser-based personal sportsbook ticket notebook and live football data testbed.

## Open and test

Use the same GitHub Pages URL supplied by the project owner. No GitHub account is required to open the published app. Each browser stores its own tickets locally; sharing the URL does not share ticket records. Export/import transfers a snapshot manually, not continuously.

To deploy this package, upload `index.html` and these documentation files to the same GitHub repository. Keep the GitHub Pages publishing configuration unchanged.

## Features

- Ticket entry and photo/OCR extraction; review extracted fields before saving.
- Ticket ledger and Positions & Crossovers with filtering and repeated-team exposure.
- Duplicate detection, export and import between browsers.
- v0.01.008: NFL live scoreboard and read-only Kalshi market-data experiment, with game-to-ticket association and refresh controls.

## Limitations

- The external live feeds have not yet been confirmed working on all tester devices.
- Kalshi outright winner probabilities are **not** spread-cover probabilities. Calibrated spread/parlay forecasts are not implemented.
- The college-football extension is **planned, not included in v0.01.008**.
- Do not rely on the app for actual wager settlement.
- Local browser data may be lost if browser storage is cleared. Export a backup before changing browsers or clearing site data.

## Tester feedback

Include version, browser/device, steps to reproduce, expected result, actual result, and optionally a screenshot with personal data removed. See TESTING.md.

## Release policy

Both testers use the same published version. Update the version number and CHANGELOG.md with every functional release; do not silently change behavior under the same version.
