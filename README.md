# KON Board — Konverto Hackathon 2026

Interactive frontend prototype for the **KON Board** challenge, based on the fictional dataset supplied for the hackathon.

## Live demonstration
https://konboard.netlify.app/

## Features
- Overview of customer organizations and usage
- Adoption trends, daily activity and organizational filters
- What People Build: types of tools, use cases, connections and sharing indicators
- Spending: AI model, image generation and web-search costs, with investigation of peaks
- Comparison of organizations, monthly budgets, revenue and costs
- Who Pays simulator: Konverto / Customer / Unassigned
- Recurring Azure infrastructure cost scenarios
- Data-quality indicators and actionable insights

## Technologies
HTML, CSS and JavaScript. Client-side application; no production backend or live Azure billing.

## Run locally
Open `index.html` in a modern web browser, or serve the folder with any static web server. No build step is required.

## Publish
Deploy the folder containing `index.html` to Netlify or another static host.

## About the data
All organizations and prices are **fictional examples supplied for the hackathon**, denominated in USD. May and November are partial months. Missing daily reports are distinct from reported zero activity; cached input tokens are already included in input tokens; breakdown records must not be added again to daily totals. The examples of KON Dash building blocks are illustrative and are not reconciled with usage totals.

## Scope
This repository contains the KON Board frontend, not a production KON Dash application. Saved financial scenarios remain local to the browser and are not synchronized across devices.

## Attribution and licensing
Challenge materials and sample data were supplied by Konverto Labs. 
