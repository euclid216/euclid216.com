# euclid216.com

One page. The mark, the wall, one line. Nothing else until public beta.

## Updating the lights

Edit `status.json` and push. The page reads it on load.

- `online`  — how many stages are complete (lit boxes; also the lit fraction of the cube)
- `of`      — the number of stages (11)
- `now`     — the stage in progress (the breathing ring); normally `online + 1`
- `public_beta` — which stage is the public beta (its box carries the only label)
- `updated` — the date of the change, local

Nothing else on the page changes. No labels, no dates, no details are ever added here.

## Files

- `index.html` — the page (self-contained; fonts from Google Fonts)
- `status.json` — the four numbers and the line; agents may poll it
- `llms.txt` — the line and a contact, for agents and crawlers
- `CNAME` — the custom domain for GitHub Pages
