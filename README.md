# Luitwieler Insurance Agencies Reporting Site

Static, self-contained performance report hub for Luitwieler Insurance Agencies, deployed on Vercel.

## Structure

- `index.html` is the report hub linking five reports: campaign overview, Auto campaign page, SEO audit, and two California research reports
- `Luitwieler-CA-ZIP-Data-10-12-26.csv` is the ZIP-level data behind the research reports
- `vercel.json` — Vercel config: clean URLs, security headers, `noindex` so the report stays out of search engines

## Deploying

No build step. In Vercel, import this repo with:

- **Framework Preset:** Other
- **Build Command:** *(leave empty)*
- **Output Directory:** *(leave empty — serves the repo root)*

Or from the CLI: `vercel --prod`

## Updating the report

Replace `index.html` with the new export and push to `main`; Vercel redeploys automatically.
