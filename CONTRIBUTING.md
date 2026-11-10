# Contributing to the AAPL Expiration Tracker

Thank you for contributing to this repository. This is a small, curated repo for the weekly AAPL options-expiration review, so please keep changes focused.

## How to contribute

1. Open an issue describing what you are tracking or changing (or an expiration date you want added).
2. Create a branch for your work: e.g. `add-expirations`.
3. Commit changes to that branch and open a pull request into the default branch (`main`).
4. Reference the tracking issue(s) in the PR description when relevant.

## Reporting market data

- All market figures must come from live data (Yahoo Finance). Do not paste stale numbers without a clear note about the date.
- If a number looks odd or inconsistent, report exactly what the source returned rather than silently fixing it.
- Include the share price used and the expiration date for every set of chain stats.

## Files

- `expirations.md` — the consolidated tracker.
- Issue titles follow the pattern `Expiry YYYY-MM-DD`.
