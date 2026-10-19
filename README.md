# BOO! — The Haunted Collection

**Tiny Haunts. Legendary Stories.**

A free, mobile-friendly pack-ripping and card collecting web app with original premium retro-Halloween card illustrations and real-legend-inspired stories.

## Play

When GitHub Pages is enabled: https://glitchedduck.github.io/boo-haunted-collection/

Pages configuration: **Settings → Pages → Deploy from a branch → main → / (root)**.

## Series 01

- **36 cards:** 21 Ghosts, 7 Tricks, 8 Haunted Locations
- Six cards per pack: 3 Common + 2 Uncommon + 1 Rare-or-better
- Rare-slot odds: 89% Rare, 10% Ultra Rare, 1% Secret Rare (prototype odds only)
- 23 redesigned premium cards (001–021, 025 and 031), each with a unique scene
- All other cards keep their existing illustrations until the remaining artwork is commissioned
- Collector binder and progress saved in the user's browser, with no payments or accounts

## Structure

- `index.html`: web app, deck data and base artwork for unreplaced cards
- `assets/premium-card-art.js`: optimized, original image data for the 23 premium cards
- Optimised artwork is bundled as data URLs for reliable GitHub Pages loading. The downloadable ZIP also contains the individual image files and a manifest.

No build is required. Serve this folder with any static web server.

**Note:** Some characters and locations are inspired by folklore and reported ghost stories, not verified supernatural events. This is a free collecting prototype, not yet a playable battle TCG. No cards have cash value.