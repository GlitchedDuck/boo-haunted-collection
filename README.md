# BOO! — The Haunted Collection 🎃

**Tiny Haunts. Legendary Stories.** A free retro-Halloween digital pack-ripping game, with a unique illustrated trading card for every card in the first set.

## Play
https://glitchedduck.github.io/boo-haunted-collection/

## Series 01: The Midnight Manor

- **36 unique illustrated cards:** 21 Ghosts, 7 Tricks and 8 Haunted Locations.
- Every card now displays a complete illustration and matching title, card number and rarity.
- All 13 former prototype/placeholder cards were redesigned, including *Cobweb Surprise* (#023) and *The Lady's Chamber* (#029).
- 6 cards per booster: 3 Common, 2 Uncommon and 1 Rare-or-better.
- Demo rare-slot odds: 89% Rare, 10% Ultra Rare and 1% Secret Rare (client-side, unaudited).
- Collection binder and duplicate count are saved locally in the same `boo-haunted-collection-v1` browser storage key as before, so players keep their progress.
- The game is free: no purchases, trading, prizes or cash value.

## Files
- `index.html` — complete game logic and booster wrapper artwork.
- `assets/premium-card-art.js` — all 36 illustrations embedded for fast, simple GitHub Pages deployment; version 3 avoids old-image caching.

Local package downloads additionally contain individually numbered `.webp` assets and `assets/manifest.json` for future game development.

## Development notes
This is a pack-opening and collection prototype, not yet a rules-complete competitive trading card game. Ghost stories are folklore/inspiration rather than historical proof. Distinctive illustration scenes were created for this original project, including a set of 13 illustrated scenes adapted into custom card layouts.

GitHub Pages setup: Settings → Pages → Deploy from branch → main → /(root).