# FeedGuard

**User-controlled filtering for YouTube feeds.**

FeedGuard is a Chrome extension that removes Shorts, AI slop, brainrot, clickbait, and low-quality content from your YouTube feed — based entirely on rules you set. No algorithm, no account, no data collection.

**Live site:** [jadenbchu123-dev.github.io/FeedGuard](https://jadenbchu123-dev.github.io/FeedGuard/)

---

## Features

- **Hide Shorts** — removes Shorts from every surface (feed, search, sidebar)
- **Hide Playables** — removes the YouTube games shelf
- **AI slop preset** — keyword filter for AI-generated and faceless content
- **Brainrot preset** — filters skibidi, sigma, gyatt, and similar
- **Clickbait preset** — filters "you won't believe", "gone wrong", "exposed", and similar patterns
- **Channel blocking** — block any channel by name
- **Keyword filtering** — block any title keyword or phrase
- **Min view count** — hide videos below a threshold you set
- **Hidden log** — see exactly what was filtered and why, with one-click allow controls
- **Export / Import** — back up and restore your settings across devices

## Privacy

All filtering happens locally in your browser. No data leaves your device. No server, no analytics, no account required.

## Status

Submitted to the Chrome Web Store — pending review. Install link coming soon.

## Tech

Vanilla JavaScript, Chrome Manifest V3, `chrome.storage` API.
