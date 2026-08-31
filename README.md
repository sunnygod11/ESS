# ESS — Routine Test Report Generator

A single-page, client-side tool that generates a one-page Thai/English routine-test
certificate for inverters connected to the MEA grid, and exports it as a PDF.

- **App:** [`routine_test_report.html`](routine_test_report.html) — a self-contained static page (no build step, no server).
- **Deploy:** static hosting on Vercel. [`vercel.json`](vercel.json) rewrites `/` to the report so the site root serves the app directly.

## Run locally
Just open `routine_test_report.html` in a browser — that's the whole app.

## Deploy on Vercel
1. Import this GitHub repo at [vercel.com/new](https://vercel.com/new).
2. Framework preset: **Other** (no build command, no output directory — it's static).
3. Deploy. The root URL serves the report via the rewrite in `vercel.json`.
