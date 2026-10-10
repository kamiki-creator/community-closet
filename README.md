# Community Closet — v0.3 private prototype

Open-source wardrobe starter for intentional reuse and free gifting. No sales, credits, or required swaps.

## Test online
Host these files at the root of a GitHub Pages repository. In Settings → Pages, choose Deploy from a branch, main, /(root). Once published, use the HTTPS URL on your phone.

## Important data warning
All wardrobe entries, photographs and measurements are stored in **this browser only** via localStorage. No login, cloud sync, server backup, or multi-device storage. Export a JSON backup regularly. Do not add sensitive information to a public GitHub repository. Public hosting of the app does **not** make local wardrobe entries public, but shared devices and browser data removal pose risks.

## v0.3 changes
- Full garment photos shown using contain, with taller portrait-friendly cards. Tap to view full-size.
- Four-column mobile navigation.
- Fixed save error handling to avoid showing unsaved entries after storage failure.
- Added PWA manifest and basic offline fallback service worker. Installability varies until proper app icons are added.
- Retains import/export, style preferences, measurements, and Learn section.

## Future architecture
React/TypeScript frontend, FastAPI API, PostgreSQL, private media storage, explicit opt-in free community listings, location privacy and moderated requests. The current prototype is not a public exchange.