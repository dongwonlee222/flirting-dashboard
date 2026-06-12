# Flirting Dashboard

Shareable static website for the Flirting operations dashboard.

## Live Site

- GitHub Pages: `https://dongwonlee222.github.io/flirting-dashboard/`

## Current Coverage

- Country-level app signup and activity dashboard
- Country detail filter for daily KPIs, gender/age, recent login, monetization, and deletion reasons
- Meta/Facebook ads CSV seed summary for paid acquisition review
- Aggregate-only dashboard output; no raw user rows, tokens, receipts, contacts, or message content

## Files

- `index.html`: dashboard page
- `chart.umd.js`: local Chart.js bundle used by the dashboard

## Local Preview

```bash
python3 -m http.server 8052
```

Open:

```text
http://127.0.0.1:8052/
```

## Deployment

This folder can be deployed as a static site through GitHub Pages, Vercel, Netlify, or any static web host.
