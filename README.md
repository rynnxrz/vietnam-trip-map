# Vietnam Trip Map

Static mobile-first trip planner for Hanoi × Phu Quoc, 2026-10-01 to 2026-10-06.

## Cloudflare Pages

Connect this repository in Cloudflare Pages.

- Production branch: `main`
- Framework preset: `None`
- Build command: leave blank
- Build output directory: `/`

The site is a single `index.html` and has no build step.

## Notes

- Main itinerary works without external JS/CSS CDN dependencies.
- Google Maps and AMap are optional outbound navigation links.
- Grab copies the destination so it can be pasted into the Grab app.
- The page includes a local edit mode; edits made there are stored only in that browser/device via localStorage.
- For shared permanent edits, update `index.html` in this repository and Cloudflare Pages will redeploy automatically.
