# The World Top 50 Lists

1,138 travel picks: a world top 50 and a US top 50 for each of 10 categories (places to visit, things to do, adventures, wellness, events, wonders, adult entertainment, beaches, nature and wildlife, wow spots), plus 138 African & Diaspora Festivals (50 in the US).

The site has a tab for each list and a World / International / Domestic (US) switch:
- **World:** the world top 50 (`data.js`).
- **International:** the world top 50 without its US entries.
- **Domestic (US):** the US top 50 (`data-us.js`). On the festivals tab, it shows the US festivals.

US entries in the world lists are detected from US city and state names, and include Puerto Rico and the US Virgin Islands. There's also a search box and a toggle to hide places with a US travel advisory. Every card links to photos and a map. Festival cards also link to the official website, or to a search for it.

## Publish on GitHub Pages

1. On GitHub, create a new public repository, for example `bestspots`.
2. Click **Add file → Upload files** and drop in `index.html`, `data.js` and this `README.md`. Commit.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. After a minute or two the site is live at `https://<your-username>.github.io/bestspots/`.

## Edit the lists

All picks live in `data.js`. Each item is one line in the form `"Name|Where or note"`, with an optional third part for the official website: `"Name|Place; date|https://..."`. Add `[Advisory]` to a name to show the advisory badge.

Safety and date notes were checked as of November 2026. Confirm advisories at travel.state.gov before booking.
