# Shoonya TV

Hosted web board for the Shoonya studio TV display.

- Public URL: https://tv.shoonyadance.com
- Source design: `projects/shoonya/tv-event-display` in the Design System repo
- Feed: https://links.shoonyadance.com/events.json
- Preview thumbnail: `thumbnail.png` is wired through Open Graph / Twitter metadata

The deployed `index.html` is the built, self-contained artifact from `dist/`. The default loop shows an Opendeurdag-led overview with five upcoming events, walks through those five events one at a time, then returns to the overview. Use `?board=events` or `?board=detail` for pinned review views; the older `?board=now` URL remains an alias for the detail view.

To update the design, rebuild from the Design System source and copy the contents of `dist/` here. Event content normally updates through the link-in-bio feed, so this repo does not need redeploying for programme changes.
