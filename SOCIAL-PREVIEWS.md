# 🔄 Social previews: refresh guide + share-image ledger

When a link to one of ORG's GitHub Pages sites is pasted into a chat app, the app shows a
preview card (title, description and a share image) that it fetched **once** and then **cached**.
After a share image or title changes, old previews keep showing until each app is told to look again.
This file lists how to do that for each app, and which pages have their own tailored share image.

*Generated 2026-10-22 by the arrival kit's `social/social-previews.mjs` (canonical copy in
[my-template](https://github.com/drasticstatic/my-template/tree/main/changelog-template/arrival/social)).
Re-run it after deploys that add pages or change share images.*

## 🧰 How to refresh each app

| App | How to make it re-fetch | Notes |
|---|---|---|
| ✈️ **Telegram** | Message [@WebpageBot](https://t.me/WebpageBot) the link (you can send several links, one per line) | The bot replies with the fresh preview; new shares use it right away |
| 💼 **LinkedIn** | Paste the link into [Post Inspector](https://www.linkedin.com/post-inspector/) | Inspecting re-scrapes the page |
| 📘 **Facebook / Messenger** | Paste into the [Sharing Debugger](https://developers.facebook.com/tools/debug/) and press **Scrape Again** | Also accepts a batch of links |
| 💬 **Discord** | No refresh tool. Share the link with a harmless suffix such as `?v=2` | Discord caches per exact URL, so a new suffix gets a new preview |
| 🟪 **Slack** | No refresh tool. Use the `?v=2` suffix trick | Old messages keep their old unfurl |
| 🐦 **X (Twitter)** | No public validator any more. Use the `?v=2` suffix, or wait (cards refresh on their own, roughly a week) | |
| 🟢 **WhatsApp** | No refresh tool. Use the `?v=2` suffix | WhatsApp caches aggressively |
| 🦋 **Bluesky** / 🐘 **Mastodon** | Fetched when a post is written; nothing to clear | Each Mastodon server fetches its own copy |
| 💬 **iMessage** | Fetched on the sender's phone at send time | Nothing to clear |

**Rule of thumb:** after changing a share image, refresh Telegram (@WebpageBot), LinkedIn and
Facebook for the pages listed below. Use the `?v=2` suffix anywhere else.

## 🖼️ Share-image ledger

44 pages checked: **42 tailored**, 2 using the default card,
0 with no share image.

### ✨ Pages with their own tailored share image

| Page | Title | Share image |
|---|---|---|
| [octagon-religious-research-group-org.github.io/donate/](https://octagon-religious-research-group-org.github.io/donate/) | Donate: ORG on GitHub | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/page/donate.jpg) |
| [octagon-religious-research-group-org.github.io/pledge/](https://octagon-religious-research-group-org.github.io/pledge/) | A pledge of support: ORG on GitHub | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/page/pledge.jpg) |
| [octagon-religious-research-group-org.github.io/map/](https://octagon-religious-research-group-org.github.io/map/) | Map: ORG on GitHub | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/page/map.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog) | Changelog: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/page/changelog.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/library](https://octagon-religious-research-group-org.github.io/changelog-astro-public/library) | Library: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/page/library.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/map](https://octagon-religious-research-group-org.github.io/changelog-astro-public/map) | Map: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/page/map.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/ledger](https://octagon-religious-research-group-org.github.io/changelog-astro-public/ledger) | Ledger: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/ledger.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/three-directions](https://octagon-religious-research-group-org.github.io/changelog-astro-public/three-directions) | Three directions, living together: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/three-directions.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site) | orgspirituality.org: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/page/changelog.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/api](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/api) | The API: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/page/changelog.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github) | ORG on GitHub: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/page/changelog.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/previews](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/previews) | Previews and proposals: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/page/changelog.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-22-every-org-chat-a-pledge-and-licenses](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-22-every-org-chat-a-pledge-and-licenses) | Every ORG chat in one window, a pledge of support, and licenses for ORG's GitHub home: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/github/2026-10-22-every-org-chat-a-pledge-and-licenses.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in) | A navbar on every page, a map with pictures, and one window for every way in: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/github/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-12-choose-how-you-arrive](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-12-choose-how-you-arrive) | Choose how you arrive: a welcome, / to search, and faces on every change: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/github/2026-10-12-choose-how-you-arrive.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-12-every-entry-shares-with-its-own-card](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-12-every-entry-shares-with-its-own-card) | Share one entry, and it arrives with its own card: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/github/2026-10-12-every-entry-shares-with-its-own-card.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-12-reading-mode-and-whats-new](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-12-reading-mode-and-whats-new) | Reading mode, and what's new since your last visit: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/github/2026-10-12-reading-mode-and-whats-new.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-12-the-ledger-every-public-change](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-12-the-ledger-every-public-change) | The ledger: every public change, in plain words: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/github/2026-10-12-the-ledger-every-public-change.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/previews/2026-10-12-three-directions-kept-as-history](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/previews/2026-10-12-three-directions-kept-as-history) | Three directions, kept as history: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/previews/2026-10-12-three-directions-kept-as-history.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-11-astrolog-moves-into-the-org](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-11-astrolog-moves-into-the-org) | The AstroLog moves into the organization, and the root page becomes a portal: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/github/2026-10-11-astrolog-moves-into-the-org.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/previews/2026-10-05-dapp-preview-takes-on-all-three-lights](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/previews/2026-10-05-dapp-preview-takes-on-all-three-lights) | The dApp preview takes on all three lights: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/previews/2026-10-05-dapp-preview-takes-on-all-three-lights.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-10-05-home-tile-labels-below-the-art](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-10-05-home-tile-labels-below-the-art) | Home tile labels move below the art: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/site/2026-10-05-home-tile-labels-below-the-art.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-05-org-github-profile-root-and-brand](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-05-org-github-profile-root-and-brand) | ORG gets a GitHub profile, a root page, and brand assets: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/github/2026-10-05-org-github-profile-root-and-brand.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/previews/2026-10-05-three-design-directions-for-a-vote](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/previews/2026-10-05-three-design-directions-for-a-vote) | Three design directions shared for a vote: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/previews/2026-10-05-three-design-directions-for-a-vote.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-10-04-blotter-perforations-across-the-art](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-10-04-blotter-perforations-across-the-art) | Perforations across the art tiles: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/site/2026-10-04-blotter-perforations-across-the-art.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-10-03-faster-home-page-images](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-10-03-faster-home-page-images) | Faster home page images: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/site/2026-10-03-faster-home-page-images.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/previews/2026-09-15-dapp-and-sidecar-previews-begin](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/previews/2026-09-15-dapp-and-sidecar-previews-begin) | Two previews begin: a dApp and a sidecar site: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/previews/2026-09-15-dapp-and-sidecar-previews-begin.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/api/2026-08-17-sign-in-moves-to-clerk](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/api/2026-08-17-sign-in-moves-to-clerk) | Member sign-in moves to Clerk: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/api/2026-08-17-sign-in-moves-to-clerk.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/api/2026-07-23-an-api-for-offerings-and-editable-pages](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/api/2026-07-23-an-api-for-offerings-and-editable-pages) | An API for offerings and editable pages: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/api/2026-07-23-an-api-for-offerings-and-editable-pages.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-07-23-offerings-shop-and-website-editor](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-07-23-offerings-shop-and-website-editor) | An offerings shop, and a way to edit the site without code: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/site/2026-07-23-offerings-shop-and-website-editor.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-07-14-monthly-meditation-ceremony-details](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-07-14-monthly-meditation-ceremony-details) | Monthly meditation ceremony details updated: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/site/2026-07-14-monthly-meditation-ceremony-details.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-07-11-one-accent-and-a-spinning-menu](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-07-11-one-accent-and-a-spinning-menu) | One accent color, and a spinning octagon menu on phones: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/site/2026-07-11-one-accent-and-a-spinning-menu.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-06-17-join-member-portal-and-search](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-06-17-join-member-portal-and-search) | A Join page, a member portal, and search across every page: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/site/2026-06-17-join-member-portal-and-search.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-06-16-home-becomes-a-perforated-sheet](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-06-16-home-becomes-a-perforated-sheet) | The home page becomes one perforated sheet: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/site/2026-06-16-home-becomes-a-perforated-sheet.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-06-15-navigation-tabs-revised](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-06-15-navigation-tabs-revised) | Navigation tabs and the About page, simplified: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/site/2026-06-15-navigation-tabs-revised.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-06-08-section-pages-move-onto-the-site](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-06-08-section-pages-move-onto-the-site) | Section pages move onto the site: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/site/2026-06-08-section-pages-move-onto-the-site.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-06-01-about-page-founding-charter](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-06-01-about-page-founding-charter) | An About page with ORG's founding charter: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/site/2026-06-01-about-page-founding-charter.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-05-25-sacred-geometry-octagon-home](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-05-25-sacred-geometry-octagon-home) | A sacred-geometry home page, with the rainbow octagon at its center: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/site/2026-05-25-sacred-geometry-octagon-home.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-05-11-the-new-site-begins](https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-05-11-the-new-site-begins) | The new site begins, with five ideas for a home page: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/changelog/site/2026-05-11-the-new-site-begins.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/library/how-orgs-sites-fit-together](https://octagon-religious-research-group-org.github.io/changelog-astro-public/library/how-orgs-sites-fit-together) | How ORG's sites fit together: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/library/how-orgs-sites-fit-together.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/library/how-this-astrolog-works](https://octagon-religious-research-group-org.github.io/changelog-astro-public/library/how-this-astrolog-works) | How this AstroLog works: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/library/how-this-astrolog-works.jpg) |
| [octagon-religious-research-group-org.github.io/changelog-astro-public/library/the-perforated-sheet](https://octagon-religious-research-group-org.github.io/changelog-astro-public/library/the-perforated-sheet) | The perforated sheet: ORG AstroLog | [image](https://octagon-religious-research-group-org.github.io/changelog-astro-public/og/library/the-perforated-sheet.jpg) |

### 🪪 Pages using the default card

- [octagon-religious-research-group-org.github.io/](https://octagon-religious-research-group-org.github.io/)
- [octagon-religious-research-group-org.github.io/changelog-astro-public/](https://octagon-religious-research-group-org.github.io/changelog-astro-public/)

## 📋 Copy-paste list for @WebpageBot

```
https://octagon-religious-research-group-org.github.io/
https://octagon-religious-research-group-org.github.io/donate/
https://octagon-religious-research-group-org.github.io/pledge/
https://octagon-religious-research-group-org.github.io/map/
https://octagon-religious-research-group-org.github.io/changelog-astro-public/
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog
https://octagon-religious-research-group-org.github.io/changelog-astro-public/library
https://octagon-religious-research-group-org.github.io/changelog-astro-public/map
https://octagon-religious-research-group-org.github.io/changelog-astro-public/ledger
https://octagon-religious-research-group-org.github.io/changelog-astro-public/three-directions
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/api
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/previews
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-22-every-org-chat-a-pledge-and-licenses
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-13-a-navbar-a-map-and-one-window-for-every-way-in
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-12-choose-how-you-arrive
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-12-every-entry-shares-with-its-own-card
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-12-reading-mode-and-whats-new
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-12-the-ledger-every-public-change
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/previews/2026-10-12-three-directions-kept-as-history
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-11-astrolog-moves-into-the-org
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/previews/2026-10-05-dapp-preview-takes-on-all-three-lights
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-10-05-home-tile-labels-below-the-art
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/github/2026-10-05-org-github-profile-root-and-brand
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/previews/2026-10-05-three-design-directions-for-a-vote
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-10-04-blotter-perforations-across-the-art
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-10-03-faster-home-page-images
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/previews/2026-09-15-dapp-and-sidecar-previews-begin
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/api/2026-08-17-sign-in-moves-to-clerk
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/api/2026-07-23-an-api-for-offerings-and-editable-pages
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-07-23-offerings-shop-and-website-editor
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-07-14-monthly-meditation-ceremony-details
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-07-11-one-accent-and-a-spinning-menu
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-06-17-join-member-portal-and-search
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-06-16-home-becomes-a-perforated-sheet
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-06-15-navigation-tabs-revised
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-06-08-section-pages-move-onto-the-site
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-06-01-about-page-founding-charter
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-05-25-sacred-geometry-octagon-home
https://octagon-religious-research-group-org.github.io/changelog-astro-public/changelog/site/2026-05-11-the-new-site-begins
https://octagon-religious-research-group-org.github.io/changelog-astro-public/library/how-orgs-sites-fit-together
https://octagon-religious-research-group-org.github.io/changelog-astro-public/library/how-this-astrolog-works
https://octagon-religious-research-group-org.github.io/changelog-astro-public/library/the-perforated-sheet
```
