# SignalCheck

Hackathon ID: AZIS-NGWZTT

SignalCheck is a static civic-tech misinformation triage interface. It runs entirely in the browser and is designed for GitHub Pages.

## Stack
- Plain HTML
- CSS
- Vanilla JavaScript
- Browser localStorage

## Run locally
Double-click `index.html`, or serve the folder with any static file server.

## GitHub Pages
Upload the files to the repository root, then use **Settings → Pages → Deploy from a branch → main → /(root)**.

## Features
- Submit a claim
- Automatic Sensational / Shouting / Unsourced flags
- High Risk when 2+ flags
- Public feed with category/status filters
- Claim detail view
- Review workflow with note
- Delete Review
- Delete Claim
- Demo/source-backed reviewed claims

Note: submitted claims and reviews are stored in the current browser's localStorage because this version intentionally has no backend or API.
