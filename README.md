# Shoonya TV

Hosted web board for the Shoonya studio TV display.

- Public URL: https://tv.shoonyadance.com
- Source design: `projects/shoonya/tv-event-display` in the Design System repo
- Feed: https://links.shoonyadance.com/events.json
- Preview thumbnail: `thumbnail.png` is wired through Open Graph / Twitter metadata

The deployed `index.html` is the built, self-contained artifact from `dist/`. It rotates the upcoming-events and now/next boards by default, with `?board=events` and `?board=now` available for pinned review views.

To update the design, rebuild from the Design System source and copy the contents of `dist/` here. Event content normally updates through the link-in-bio feed, so this repo does not need redeploying for programme changes.
