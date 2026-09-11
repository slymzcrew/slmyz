# slymz — landing page

static site, no build step.

## deploy on github pages
1. create a repo (e.g. `slymz-site`) and upload everything in this folder (keep `assets/` and `whitelist.json` next to `index.html`).
2. repo → settings → pages → source: **deploy from a branch**, branch `main`, folder `/ (root)`.
3. wait a minute, then open `https://<username>.github.io/<repo>/`.

## update the whitelist
edit `whitelist.json` — one address per entry, lowercase or checksummed both work:
```json
{ "addresses": ["0xabc…", "0xdef…"] }
```
commit → the checker picks it up on the next page load.

## replace the hero video
overwrite `assets/hero.mp4` (h.264, muted, ideally ≤ 5 mb, seamless loop).

## links to fill in
search `index.html` for `opensea.io/collection/slymz`, `x.com/slymz`, `discord.gg/slymz`, `shop.slymz.xyz`.
