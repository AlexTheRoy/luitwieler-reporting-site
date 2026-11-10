# Luitwieler Insurance Agencies Reporting Site

Static client reporting site for Luitwieler Insurance Agencies (GOAL account #167), deployed on Vercel.

## Structure

- `index.html`: hub with Campaign Reports and Website & Research sections
- Campaign Reports, since launch (Oct 1, 2024 through Nov 10, 2026, with 2026 year to date as context):
  - `Luitwieler-Campaign-Overview-Since-Launch-11-10-26.html`: all campaigns, Marketplace included
  - `Luitwieler-Auto-Campaign-Performance-Since-Launch-11-10-26.html`: every Auto quote funnel, with a comparison panel
  - `Luitwieler-Home-Campaign-Performance-Since-Launch-11-10-26.html`: Home
  - `Luitwieler-Monthly-Sales-by-Source-11-10-26.html`: every month since October 2024 by source and ad channel, with the ad channels that have the fewest quotes and binds
  - `Luitwieler-Source-ZIP-Sales-Since-Launch-11-10-26.html` and `Luitwieler-ZIP-Sales-11-10-26.csv`: sales by source, ad channel, county and ZIP
  - `Luitwieler-Inbound-Call-Review-11-10-26.html`: inbound call review, Aug 12 to Nov 10, 2026 (the last 90 days)
- Website & Research (Oct 12, 2026):
  - `Luitwieler-SEO-Audit-10-12-26.html`: agency web page and local listings audit
  - `Luitwieler-CA-*`: California demographic and wildfire research, plus the ZIP CSV
- `vercel.json`: clean URLs, redirects from the 11-04-26 file names to the 11-10-26 ones, security headers, `noindex`

No build step. Push to `main` and Vercel redeploys.
