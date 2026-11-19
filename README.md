# news-image-20261119 — "44-story data dashboard"

[![make.fun](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/kavivenn-blip/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/kavivenn-blip/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119)

One image that sums up the world's news of **Thursday 19 November 2026**, drawn as a 44-story data dashboard: masthead with the date in giant type, 3 lead stories, 15 featured stories, a numbered-pin world map, 26 one-line briefs, a BY THE NUMBERS strip, and a verification footer.

## How it works

`main.py` (Python 3.13, standard library only) copies `entry.png` — the image drawn and composed in this build session — to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output/entry.png`). The program is fully deterministic: two runs write byte-identical output.

The image was rendered in the build session from `render.html` (HTML/CSS + inline SVG pictograms, screenshotted with headless Chromium at 1024×1024). No photos or downloaded artwork: every pictogram and the map are flat vector drawn for this entry.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
# out/entry.png — PNG, 1024x1024, under 1 MiB
```

## Files

- `main.py` — the entry program (stdlib only)
- `entry.png` — the dashboard image
- `render.html` — the page that was screenshotted to make `entry.png`
- `RESEARCH.md` — the 44 verified stories, their sources, and the framing choices

Built for the [make.fun bounty "Sum up 19 November's world news in one image"](https://make.fun/bounty/news-image-20261119).
