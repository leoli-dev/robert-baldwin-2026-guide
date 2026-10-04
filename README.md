# Robert-Baldwin 2026 · Voter Guide

An independent, unofficial one-page guide to the seven candidates in the **Robert-Baldwin** electoral district for the **Québec general election on October 5, 2026**.

🔗 **Live site:** https://leoli-dev.github.io/robert-baldwin-2026-guide/

I made this for my own community. It gives sources to compare — it does **not** recommend whom to vote for.

## What's in the guide

- The election: what is being decided, and when and where to vote
- The Robert-Baldwin district and the official electoral map
- Population profile of the district
- The seven candidates: background and platforms
- A source-based public-record review
- A full list of sources

## Languages

The page switches language instantly, with no reload and no translation service:

| Language | Code |
| --- | --- |
| Français | `fr` |
| English | `en` |
| 简体中文 (Mandarin) | `zh-Hans` |
| 繁體中文 (Cantonese) | `yue-Hant` |

## Where to vote

Your polling place depends on your address, so it is not listed here. Use the official lookup: [Élections Québec — Where and when to vote](https://www.electionsquebec.qc.ca/voter/ou-et-quand-voter/).

## Technical notes

- A single static page, `index.html`: plain HTML, CSS and JavaScript. No build step and no backend. The page has no advertisements and no forms that collect personal data.
- Visit statistics are collected with Google Analytics (GA4) and used for that purpose only. The page states this in its privacy note.
- The official district map is a static render of page 1 of the Élections Québec 2026 Île-de-Montréal PDF, stored at `assets/map-montreal.jpg`. The original PDF and the official interactive map are linked from the page.
- Candidate photos and party logos are loaded remotely from their original public sources, so they need a network connection.
- Favicon files: `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png` and `icon-192.png`.
- Hosted on GitHub Pages, served from the root of the `main` branch.

### Run locally

```bash
git clone https://github.com/leoli-dev/robert-baldwin-2026-guide.git
cd robert-baldwin-2026-guide
python3 -m http.server 8000   # then open http://localhost:8000
```

Opening `index.html` directly in a browser also works.

### Update the content

Edit `index.html` and push to `main`. GitHub Pages republishes automatically, usually within 1–2 minutes.

## Disclaimer

- This page is not affiliated with Élections Québec, any political party, or any candidate. Always verify against official sources.
- Information was reviewed on October 4, 2026. If anything differs from official sources, the official sources prevail.
- Photos, logos and quoted material remain the property of their respective owners and are used here for informational purposes. To request removal, please open an issue.

## Feedback

Spotted an error? Please [open an issue](../../issues).
