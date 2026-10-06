# Cottonwood Operations Dashboard

Ready-to-upload static website. No npm install, build command, server, ChatGPT account, or ChatGPT hosting is required.

## Upload and publish
1. Create the repository `cottonwood-operations-dashboard`.
2. Extract this ZIP and upload its contents. `index.html` must be at the repository root, beside `app.js`, `style.css`, and `pages.json`.
3. Commit the files to `main`.
4. Open Settings → Pages → Deploy from a branch → main → /(root) → Save.
5. Open the website URL shown by GitHub Pages after deployment finishes. The repository file viewer is not the website.

GitHub Pages availability depends on your account and repository visibility. A private repository does not necessarily make its Pages website private. No business records or credentials are included in this package.

## Included
- All 24 sections from the published reconstructed dashboard; original navigation groups, unit colors, weather/WeatherBug/river links, static branding, no moving animals.
- Working page navigation, record forms, edits, search, unit filters, CSV export, printing, and shared Screwdriver/MISO dates with separate levels.
- Existing Box folder destinations in `pages.json`; the upload section opens the Update & Review folder directly in Box.
- Empty starting records. No sample invoices, sample balances, or fabricated operating values.

## Data behavior
Record forms and alerts save in the current browser at this website address. They are not shared with other devices or automatically written to Box. Export important records using the page CSV export before clearing browser data. Records from a different website address do not transfer automatically.
Box buttons open your existing folders and require your normal Box permissions. Upload files in Box itself. Automatic document extraction, invoice matching, live weather/river/lightning feeds, shared database storage, SharePoint, and Power BI are not connected. Conditions remain blank rather than showing invented values. Approved safety documents remain authoritative.

## Files
- index.html — full dashboard shell and dialogs
- style.css — responsive layout, unit colors and print styling
- app.js — navigation, forms, records, reports and alert controls
- pages.json — sections and Box folder destinations
- .nojekyll — serve the files directly
- .gitignore — exclude local junk and secrets
- README.md — these upload instructions

## Copilot handoff
Preserve this layout and all navigation. Publish this static site at the repository root using GitHub Pages; no build is required. Keep Box folder links intact. Do not seed fake records or require ChatGPT hosting. Any later shared storage or automatic Box integration requires an authenticated service; do not put credentials in browser JavaScript or claim folder links provide automatic synchronization.
