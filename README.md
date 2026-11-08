# The World Top 50 Lists

638 travel picks across 11 lists: places to visit, things to do, adventures, wellness, events, wonders, adult entertainment, beaches, nature and wildlife, wow spots, and 138 African & Diaspora Festivals (50 in the US).

The site has a tab for each list, an All / International / Domestic (US) switch that filters every tab, a search box, and a toggle to hide places with a US travel advisory. Domestic picks are detected from US city and state names in each item, and include Puerto Rico and the US Virgin Islands. Every card links to photos and a map. Festival cards also link to the official website, or to a search for it.

## Publish on GitHub Pages

1. On GitHub, create a new public repository, for example `bestspots`.
2. Click **Add file → Upload files** and drop in `index.html`, `data.js` and this `README.md`. Commit.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. After a minute or two the site is live at `https://<your-username>.github.io/bestspots/`.

## Edit the lists

All picks live in `data.js`. Each item is one line in the form `"Name|Where or note"`, with an optional third part for the official website: `"Name|Place; date|https://..."`. Add `[Advisory]` to a name to show the advisory badge.

Safety and date notes were checked as of November 2026. Confirm advisories at travel.state.gov before booking.
