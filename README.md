# Riffle Marketing Site

Landing page for [Riffle](https://riffle.run), a GPS-powered fishing trip tracker for iOS. The app automatically logs trips, routes, and catches. No manual entry required.

## What's here

Static marketing site hosted on GitHub Pages. No framework, no build step.

- `index.html`: main landing page (hero, features, how it works, beta signup)
- `privacy.html`: privacy policy
- `terms.html`: terms of use
- `global.css`: shared styles (design tokens, nav, footer)
- `CNAME`: custom domain config (`riffle.run`)

## Running locally

Just open `index.html` in a browser, or run a local server to avoid any iframe quirks:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploying

Push to `main`. GitHub Pages serves from the repo root automatically.

## Tech

Plain HTML, CSS, and vanilla JS. Beta signup is embedded via [Tally.so](https://tally.so).
