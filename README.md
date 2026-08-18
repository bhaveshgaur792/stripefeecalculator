# Fee Ledger — Stripe Fee & Reverse Invoice Calculator

A free, single-page tool to calculate Stripe payment processing fees and reverse-engineer invoice amounts — built with zero dependencies, zero backend, and zero tracking.

**Live site:** https://stripefeecalculator.vercel.app/

## What it does

- **Forward mode:** Enter the amount you're charging a client, instantly see Stripe's cut and your net payout.
- **Reverse mode:** Enter the amount you *need to receive*, and the tool calculates the exact invoice amount to charge so the client effectively covers Stripe's fees.
- Covers UK, US, EU, India, Australia, Canada, and Singapore pricing, including domestic vs. international card surcharges and currency conversion fees.
- One-click "Copy Breakdown" for pasting into invoices or client emails.
- Dark mode, fully responsive, works offline.

## Why

Most Stripe fee calculators online only do the forward calculation and don't account for country-specific international/FX surcharges accurately. This tool adds a reverse "gross-up" calculator and keeps rates aligned with Stripe's actual published pricing pages.

## Tech stack

Plain HTML, CSS, and vanilla JavaScript — no frameworks, no build step, no external JS dependencies. Deployed on Vercel.

## Rates

Rates are based on Stripe's publicly available pricing information, last reviewed August 2026. This project is an independent reference tool and is not affiliated with, endorsed by, or sponsored by Stripe, Inc. Always confirm exact rates in your own Stripe Dashboard.

## License

Free to use. No warranty — verify fees independently before relying on them for financial decisions.
