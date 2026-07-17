# Emirates Airline Interview Questions

A single-page web app that displays Emirates Airline Customer Service online interview questions behind a $1.21 paywall.

## Features

- **Free preview** — Questions 1 & 2 are visible immediately, no payment required.
- **Paywall** — Questions 3–6 and the Language Assessment section are hidden until unlocked.
- **Stripe payment** — One-click payment via a hosted Stripe Payment Link.
- **Instant unlock** — Candidates who have already paid click "I already paid" to reveal content client-side (no backend required).
- **Emirates branding** — Red & beige colour scheme, clean professional layout.
- **Fully responsive** — Works on desktop and mobile in all modern browsers.

## Setup

1. **Add your header photo** — Place a wide photo of airline staff in uniform named `header-photo.jpg` in the repository root (same folder as `index.html`). If the image is missing, a red gradient fallback is shown automatically.

2. **Deploy to GitHub Pages** — Go to *Settings → Pages*, set the source to the `main` branch root (`/`), and save. Your site will be published at `https://<your-username>.github.io/<repo-name>/`.

## Files

| File | Description |
|------|-------------|
| `index.html` | The complete single-page application |
| `header-photo.jpg` | *(You provide)* Wide banner photo of airline staff |

## Payment Link

The Stripe payment button uses the link:  
`https://buy.stripe.com/4gMfZacO50fYbNA1Hs93y04`

To change the price or replace the link, edit the `href` attribute of the `.btn-pay` anchor element in `index.html`.
