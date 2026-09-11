# slymz — landing page

static site, no build step.

## deploy on github pages
1. create a repo (e.g. `slymz-site`) and upload everything in this folder (keep `assets/` next to `index.html`).
2. repo → settings → pages → source: **deploy from a branch**, branch `main`, folder `/ (root)`.
3. wait a minute, then open `https://<username>.github.io/<repo>/`.

## whitelist (google sheet)
the checker reads this sheet live: https://docs.google.com/spreadsheets/d/1aFNIcMI_nntBEwNVVWmZgdhFFYO61uPLv5BZz2YJ6mY/edit
- tab `gtd`: paste wallet addresses anywhere in the tab (one per cell)
- tab `fcfs`: same
- sharing must stay "anyone with the link → viewer". tab names must stay exactly `gtd` and `fcfs`.
results: not on the list / gtd slot / fcfs slot (an address in both tabs counts as gtd).

## replace the hero video
overwrite `assets/hero.mp4` (h.264, muted, ideally ≤ 5 mb, seamless loop).

## links to fill in
search `index.html` for `opensea.io/collection/slymz`, `x.com/slymz`, `discord.gg/slymz`, `shop.slymz.xyz`.
