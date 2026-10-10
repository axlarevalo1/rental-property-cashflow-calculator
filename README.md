# Rental Property Cashflow & ROI Calculator

Standalone, mobile-friendly static website for Sell With Ariell Real Estate Team (CIR Realty).

## Deploy on GitHub Pages

1. Create a public repository named `rental-property-cashflow-calculator` under your GitHub account.
2. Upload `index.html` from this folder to the repository root and commit to `main`.
3. Under **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
4. Wait until GitHub shows the live Pages URL. It should follow the pattern `https://YOUR-USERNAME.github.io/rental-property-cashflow-calculator/`. Use the exact URL GitHub shows.
5. Add that URL to the WordPress iframe embed (see `wordpress-embed.txt`).

## Features

- Canadian mortgage payment convention and owner-occupied insured mortgage premium estimates where applicable
- Rental income, expenses, cashflow, cash-on-cash and ROI metrics
- 1-, 5-, and 10-year projections including annualized CAGR-equivalent
- Self-contained PDF export (no external JavaScript library required)
- Email preparation via email client, **not automatic server delivery**

## Before publishing

- Test mortgage/CMHC assumptions and Calgary property-tax estimates against current guidance.
- Test PDF downloads on mobile and WordPress, including Safari.
- GHL automatic emailing and PDF attachment delivery are **not connected**. The visitor email form currently prepares an email in their email application. Do not describe it as an automated PDF email service.
- Do not put API keys, webhooks with secrets, or personal leads into a public GitHub repository.

### Disclaimer

Educational illustrations only, not individualized lending, tax, legal, or investment advice. Less than 20% down is generally an insured owner-occupied financing scenario, not an ordinary non-owner-occupied rental purchase.
