# Gnana Yadeswar — portfolio

Static, editable portfolio with a local Three.js warehouse, clickable project bays, keyboard-accessible project links, and project story dialogs. No build step required.

## Preview

Serve this directory over HTTP, for example `python3 -m http.server 4173 --bind 127.0.0.1`.

## Files

- `index.html`: homepage content and project previews.
- `style.css`: typography, layout, responsive styles.
- `app.js`: project stories and original 3D scene.
- `assets/`: vendored Three.js 0.180.0 modules and license.

## Vercel

Import this directory as the project root. Choose Other, leave the build command empty, and serve the root directory. `vercel.json` provides basic security headers. No environment variables are required.

Google Fonts provides DM Sans, Instrument Serif, and IBM Plex Mono with local system fallbacks. The warehouse renderer is self-hosted; WebGL failure leaves all project content accessible.

## Content notes

Threadly is labeled in development. StockFlow preview is a designed summary of observed features, not a screenshot or measured business result. ₹97,000 is team revenue, not profit. VIP is excluded. Public contact currently uses the supplied LinkedIn profile. Resume and phone are not published.
