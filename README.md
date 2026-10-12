[![Mistara: Your losses kept developing. Your collateral didn't.](og-image.png)](https://mistara.space)

# Mistara

**Reinsurance collateral, verified at its source and re-tested against your losses every month.**

[Website](https://mistara.space) · [Cover Ratio check](https://mistara.space/#cover-ratio) · [Pricing](https://mistara.space/#pricing) · [Contact](mailto:founder@mistara.space)

---

## The problem

When an insurer cedes risk to a reinsurer, it still owes every claim if that reinsurer fails. The collateral behind the reinsurance (a letter of credit, a trust, funds withheld) is the only proof the promise will be kept.

That collateral is set when the treaty is signed and reviewed about once a year. Casualty losses keep developing for a decade. So the proof is checked against the past, and a cedent usually finds out the collateral wasn't real, or wasn't enough, after the counterparty has already failed.

## What Mistara does

Mistara reads the paper, the losses, the collateral and the counterparty together, every month:

| Part | What it does |
| --- | --- |
| **Security Compiler** | Turns treaties, letters of credit, trust agreements and side letters into a register of every collateral obligation, with the clause behind each one. |
| **Source Check** | Confirms letters of credit with the issuing bank and reconciles trustee statements line by line, instead of trusting the PDF. |
| **Development Engine** | Re-estimates the exposure the collateral has to cover from current loss development. Your actuary confirms. |
| **The Clock** | Tracks every expiry, non-renewal notice, true-up and top-up window, each with a named owner. |
| **Demand Composer** | Drafts top-up demands, draw presentations and notices. A person on your team signs and sends every one. |
| **Cover Ledger** | One number per program and counterparty: the Cover Ratio. |

**Cover Ratio** = verified collateral ÷ the collateral your treaty would require on today's loss estimates. Below 1.00 means a shortfall.

## Who it's for

- **Cedent edition:** fronting, program and specialty carriers, and life and annuity insurers with collateralised or offshore reinsurance.
- **Capital edition:** reinsurers, sidecars, ILS funds and captives that post collateral and want to prove it once to every cedent.

## Try it

The [Cover Ratio check](https://mistara.space/#cover-ratio) runs in your browser. Enter ceded reserves, the treaty percentage and your verified collateral to see the ratio, the shortfall and the date a letter of credit must be replaced or drawn. Nothing leaves the page.

## Status

Mistara was founded in 2026 and is at pre-seed. We are taking our first design partners: carriers with collateralised cessions on long-tail casualty. Start with a fixed-fee **Collateral Sweep** of your book, credited against your first year's subscription.

**Founder:** [Abhisar Mehta](https://www.linkedin.com/in/abhisarmehta/) · [founder@mistara.space](mailto:founder@mistara.space)

---

## About this repository

This repository hosts the static website at [mistara.space](https://mistara.space), served by GitHub Pages. The product itself is not in this repository.

| File | Purpose |
| --- | --- |
| `index.html` | The site: one self-contained page with inline CSS and JavaScript, no build step |
| `404.html` | Not-found page |
| `CNAME` | Custom domain for GitHub Pages |
| `.nojekyll` | Serves files as they are, without Jekyll processing |
| `robots.txt`, `sitemap.xml` | Search engine crawling and indexing |
| `llms.txt` | Plain-text summary for AI search tools |
| `site.webmanifest`, `favicon.svg`, `*.png` | Icons and the social share image |
| `.well-known/security.txt` | Security contact |
| `humans.txt` | Team credits |

To update the site, edit `index.html` and commit to `main`. GitHub Pages redeploys in about a minute.

---

© 2026 Mistara. Product screens and examples on the site use illustrative data.
