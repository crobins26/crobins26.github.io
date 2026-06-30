# GitHub Pages Deployment Steps

This package is designed for the repository:

`crobins26.github.io`

## Critical fix

GitHub Pages file paths are case-sensitive. The live site will show missing images or broken downloads if the `files/` and `assets/` folders are not uploaded with `index.html`.

Upload **all** of these items to the root of the repository:

- `index.html`
- `404.html`
- `README.md`
- `robots.txt`
- `sitemap.xml`
- `files/` folder
- `assets/` folder

Do not upload only `index.html`.
Do not upload the ZIP file itself into GitHub and expect GitHub Pages to unzip it.
Do not upload the containing folder only. The files must sit at the repository root.

## Fastest GitHub web upload method

1. Go to `https://github.com/crobins26/crobins26.github.io`
2. Click **Add file**.
3. Click **Upload files**.
4. Open this downloaded package on your computer.
5. Drag the **contents** of the package into GitHub, not just the unopened ZIP.
6. Confirm that GitHub shows:
   - `index.html`
   - `files/cernice-robinson-executive-capability-brief.pdf`
   - `files/simulated-cpg-po-automation-case-study.pdf`
   - `files/synthetic-dsd-kpi-dashboard.xlsx`
   - `files/portfolio-project-catalog.pdf`
   - `assets/dashboard-preview.png`
7. Commit directly to the `main` branch.
8. Wait 1-3 minutes, then refresh `https://crobins26.github.io/`.

## Test links after upload

Open these directly in your browser after the commit:

- `https://crobins26.github.io/files/cernice-robinson-executive-capability-brief.pdf`
- `https://crobins26.github.io/files/simulated-cpg-po-automation-case-study.pdf`
- `https://crobins26.github.io/files/synthetic-dsd-kpi-dashboard.xlsx`
- `https://crobins26.github.io/files/portfolio-project-catalog.pdf`
- `https://crobins26.github.io/assets/dashboard-preview.png`

If any of those show 404, the matching file or folder was not uploaded to the repository root.

## Privacy note

This portfolio uses fictional company names and synthetic data. It should not disclose real employer data, internal process details, confidential retailer relationships, or proprietary workflow logic.
