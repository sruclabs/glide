# Glide — Universal TV Remote

One remote, every television. Glide turns your Android phone into the only remote the living room needs — power, volume, input, and navigation over your home network.

**Live:** https://sruclabs.studio/glide/
**Status:** In work · Native Android only
**Studio:** [Sruc Labs](https://sruclabs.studio)

## Compatibility

Roku, LG webOS, Samsung Tizen, Android TV, Fire TV, Vizio SmartCast, Hisense VIDAA.

No account needed. Local pairing over your home network.

## Stack

Static product page. Plain HTML / CSS / JS, no build.

- `index.html` — product page (Features, Compatibility, How it works, FAQ, Download)
- `css/style.css` — Glide theme
- `js/main.js` — menu, reveal, year
- `assets/brand/favicon.svg` — icon

Google Play URL is a `#download` placeholder until the listing is live (see `PLAY URL` comments in `index.html`).

## Run locally

```zsh
python3 -m http.server 8000
# from repo root, then open the studio server path:
# http://localhost:8000/glide/ (when served from the studio repo folder)
```

Or serve this folder directly and open `/`.

## Deploy

Push to `main` → GitHub Pages (project site) → served as `/glide/` under `sruclabs.studio`.
No `CNAME` in this repo — the custom domain is set once on the studio user site.
