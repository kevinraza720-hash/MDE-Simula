# MDE Simula — Interactive property finance estimator

A lightweight, responsive mortgage repayment estimator built by **Malagasy Developer Enterprise (MDE)**.

## Live pages

| Language | Calculator | For estate agencies |
| --- | --- | --- |
| English | [Mortgage demo](https://kevinraza720-hash.github.io/MDE-Simula/en.html) | [Pilot offer](https://kevinraza720-hash.github.io/MDE-Simula/offer.html) |
| Français | [Simulateur immobilier](https://kevinraza720-hash.github.io/MDE-Simula/) | [Offre pilote](https://kevinraza720-hash.github.io/MDE-Simula/offre.html) |

## Features

- Property purchase price, deposit, nominal annual rate and term
- Optional annual insurance on **initial principal**, optional up-front costs
- Estimated fixed-rate amortising monthly repayment and total cost
- Instant comparison of three terms (current term ± 5 years, within limits)
- CSV export of a monthly amortisation schedule
- Print / save as PDF; copy a short summary
- Currencies: EUR, GBP, USD and MGA (currency switch **does not convert values**)
- Client-side calculations. No personal data submitted to an MDE server by this demo.

## Intended scope and limitations

The estimator is **illustrative only**; it does not provide financial advice, affordability tests, mortgage approvals or regulated APR/TAEG. It does not calculate property taxes, stamp duty or lender-specific products; users may estimate some additional up-front costs manually. It assumes a constant nominal annual interest rate and repayment term. Insurance, if entered, is a constant monthly charge calculated from the original loan amount.

**Never present these estimates as an offer by a lender.** Deployments for a specific jurisdiction require review of local rules, financial assumptions and disclosures.

## Commercial pilot

Proposal under validation: €149 for initial customisation and feasible integration, subject to written scope, website compatibility and a single revision round. Optional ongoing maintenance is separate, only if provided. This is **not** a confirmed market price or an established sale.

Business enquiries: [mde.officialmg@gmail.com](mailto:mde.officialmg@gmail.com).

## Structure

- `index.html`: French calculator (default GitHub Pages index)
- `en.html`: English calculator (GBP defaults)
- `offre.html`: French offer page
- `offer.html`: English offer page

Hosted as static files by GitHub Pages. No database, account system, built-in email sending or payment integration.

## Next milestones

1. Browser/device regression checks for both languages and boundary calculations.
2. Configurable white-label theme (branding, logo and client-specific defaults).
3. Commercial qualification and outreach using separate private business records.
4. Validate obligations and integration requirements before a client installation.

MDE — Malagasy Developer Enterprise · November 2026.
