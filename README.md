# The World Top 50 Lists

500 worldwide travel picks across 10 categories: places to visit, things to do, adventures, wellness, events, wonders, adult entertainment, beaches, nature and wildlife, and wow spots.

The site has a tab for each category, a search box across all 500 picks, and a toggle to hide places with a US travel advisory.

## Publish on GitHub Pages

1. On GitHub, create a new public repository, for example `bestspots`.
2. Click **Add file → Upload files** and drop in `index.html`, `data.js` and this `README.md`. Commit.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. After a minute or two the site is live at `https://<your-username>.github.io/bestspots/`.

## Edit the lists

All picks live in `data.js`. Each item is one line in the form `"Name|Where or note"`. Add `[Advisory]` to a name to show the advisory badge. Keep 50 items per category so the ranks stay 1 to 50.

Safety and date notes were checked as of November 2026. Confirm advisories at travel.state.gov before booking.
