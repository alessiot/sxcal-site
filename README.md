# SX/Cal — website

Marketing page, Privacy Policy, and Support page for [SX/Cal](https://github.com/alessiot/sxcal),
served as a static site via GitHub Pages.

## Structure

- `index.html` — the marketing page
- `privacy.html` — Privacy Policy
- `support.html` — Support / FAQ
- `page.css` — shared styles for the privacy/support pages
- `assets/` — logo, favicon, and App Store screenshots (sourced from the
  app repo's `Snapshots/6.5in/`)

Plain HTML/CSS, no build step. `.nojekyll` disables GitHub Pages' default
Jekyll processing (not needed here, and Jekyll otherwise ignores any file
or folder starting with `_`).

## Updating

Edit the HTML directly and push to `main` — GitHub Pages redeploys
automatically. If the app's copy in `STORE_LISTING.md` (in the app repo)
changes, mirror the relevant section here too; there's no automation
linking the two.

## Public contact address

`exo.ai@icloud.com` — used throughout (footer, Support, Privacy Policy).
Not a personal address; keep it that way for anything published here.
