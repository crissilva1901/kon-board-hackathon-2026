# KON Board — Konverto Hackathon 2026

Interactive, browser-based analytics and financial scenario prototype for the Konverto Labs Hackathon 2026.

**Live demo:** https://konboard.netlify.app/

## Repository structure

- `index.html` — page structure, navigation and dashboard components
- `style.css` — purple / dark-green visual identity and responsive styles
- `app.js` — analytics, controls, visualizations, filtering and financial simulator
- `data.json` — fictional hackathon dataset supplied for the challenge

## Features

- Adoption analytics and usage trends
- What People Build: assets, use cases, combinations and sharing
- AI spending and data exploration
- Cross-organization comparison
- Who Pays: customer / Konverto / unassigned cost allocation and recurring Azure cost scenarios
- Data quality and insights, including missing reports versus recorded zeros

## Run locally

Because the app loads `data.json` using `fetch()`, **do not open `index.html` directly from the filesystem**. Serve this folder using a static HTTP server.

With Python installed:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in a browser.

For the public demonstration, deploy all four files **together** at the root of a static host such as Netlify. The live website is a separate deployment and will not update automatically merely because this GitHub repository changes, unless a GitHub-to-Netlify integration is configured.

## Data and scope

The dataset includes fictional organizations, expenses, AI models, daily reports and KON Dash usage examples for the hackathon. May and November are partial months. A missing usage report is not the same as a report with zero activity. Cached input tokens are part of input totals. The sample KON Dash records are not directly reconciled with usage totals.

This is a **frontend demonstration**, not a production billing application. Scenario changes are stored in each browser's local storage, not in a shared backend. No live Azure billing or third-party API integration is performed.

## Permissions

Konverto Labs supplied the challenge materials and sample data. Confirm redistribution permissions before making the repository public or sharing it outside the hackathon. This repository does not include an open-source license.