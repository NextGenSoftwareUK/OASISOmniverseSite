# OASIS Omniverse — oasisomniverse.one

The main ecosystem site for the OASIS Omniverse — the unified Web4 + Web5 platform powering interoperable metaverses, shared quests, cross-chain assets and a new digital civilisation.

## Overview

This is a static HTML/CSS/JS site adapted from the NFT Founders Landing Page design. It serves as the top-level hub for the entire OASIS ecosystem, linking out to all sub-sites and products.

**Live site:** [oasisomniverse.one](https://oasisomniverse.one)

## Ecosystem

| Site | URL | Description |
|---|---|---|
| **Main Hub** | oasisomniverse.one | This site |
| **Web4** | web4.oasisomniverse.one | WEB4 identity, data and reputation layer |
| **StarNet** | starnet.oasisomniverse.one | Web5 app and asset store |
| **OPortal** | oportal.oasisomniverse.one | OASIS avatar and wallet portal |
| **Founders NFT** | founders.oasisomniverse.one | Founders NFT campaign (170 slots) |
| **Web4 API** | api.web4.oasisomniverse.one | WEB4 OASIS REST API (Swagger) |
| **StarNet API** | api.starnet.oasisomniverse.one | WEB5 STAR REST API (Swagger) |

## Structure

```
OASISOmniverseSite/
├── index.html        # Single-page site (all CSS and JS inline)
└── img/              # Image assets
    ├── ECOSYSTEM.jpg
    ├── HOLONET.jpg
    ├── ogengine.jpg
    ├── starnet.jpg
    ├── web4.jpg
    ├── web5.jpg
    └── ...
```

## Page Sections

- **Hero** — OASIS OMNIVERSE branding, animated orbital logo, CTAs
- **Web5: The Omniverse** — OGEngine, Our World, ODOOM, OQuake, StarNet, OAPPs, Shared Quests, Universal Inventory
- **OGEngine** — Omniverse Game Runtime detail section
- **StarNet** — Web5 app and asset store detail section
- **Web4: The Foundation** — Identity/Avatar, Karma, COSMIC ORM, HyperDrive, NFTs, Universal Wallet, ONODE API
- **Technology** — 40+ provider integrations (chains, storage, identity) and protocol architecture
- **Ecosystem Cards** — Links to all sub-sites
- **Founders CTA** — Link to founders.oasisomniverse.one
- **Developers** — Web4 API, StarNet API, STAR CLI/ODK, documentation links
- **Footer** — Full site map

## Design

- **Aesthetic:** Dark space / sci-fi — deep navy background, cyan (`#00e5ff`) accent, animated star canvas, CRT scanline overlay
- **Fonts:** Orbitron (headings), Rajdhani (body), Share Tech Mono (labels/tags)
- **Animations:** Animated orbital logo ring, pulsing title glow, scroll-reveal on all cards and sections
- **Responsive:** Mobile nav hamburger menu, single-column layouts on small screens

## Deployment

Pure static HTML — no build step required. Deploy to any static host:

- **Railway** — connect repo, set root directory, Railway will serve `index.html`
- **Cloudflare Pages** — connect repo, no build command needed
- **Vercel** — connect repo, framework: Other, output directory: `.`

## Related Repositories

- [OASIS](https://github.com/NextGenSoftwareUK/OASIS) — Main OASIS platform (Web4 API, STAR CLI/ODK, OGEngine)
- [NFTFoundersLandingPage](https://github.com/NextGenSoftwareUK/NFTFoundersLandingPage) — Founders NFT campaign site (founders.oasisomniverse.one)

## Links

- [oasisweb4.com](https://www.oasisweb4.com/) — Existing Web4 site (redirects to web4.oasisomniverse.one)
- [ourworldthegame.com](https://ourworldthegame.com) — Our World flagship game
- [OASIS Whitepaper](https://github.com/NextGenSoftwareUK/OASIS/blob/master/Docs/THE_OASIS_COMPREHENSIVE_WHITEPAPER.md)
- [Our World Whitepaper](https://github.com/NextGenSoftwareUK/OASIS/blob/master/Docs/OUR_WORLD_WHITEPAPER.md)
- [Investor Evaluation Guide](https://github.com/NextGenSoftwareUK/OASIS/blob/master/Docs/INVESTOR_EVALUATION_GUIDE.md)

---

© 2025 Next Gen Software. OASIS is open source — MIT Licensed.
