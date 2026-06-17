# Michaels Corner

The public personal-brand resource hub for Michael Florian (@michaelflorian_ai).

A generous resource hub, not a sales funnel: prompt routines you can copy, small tools and calculators, links out to the YouTube channel, and an about page. Brand and strategy live in `../brand/`.

Live (GitHub Pages): https://off-plate.github.io/michaelscorner/
Intended domain: michaelscorner.com

## What this is

A single static page. The design was built in Claude Design and is implemented faithfully here as `index.html` (the `x-dc` template) plus `support.js` (the Claude Design runtime, which loads React from a CDN and mounts the page on load). No build step.

Screens: Home, Routines (prompt library + prompt detail), Tools (tool shed + tool detail with a live AI cost calculator), Channel, About.

## Run locally

```
python3 -m http.server 8000
# open http://localhost:8000
```

Must be served over http(s), not opened as a `file://` URL (the runtime fetches its own source on boot).

## Still placeholder, fill in before promoting

- Real photo of Michael (hero + about currently show a striped placeholder).
- Real social links. The header/footer links point at generic `instagram.com` / `youtube.com` / `x.com`. Strategy says LinkedIn is primary, so add the real LinkedIn URL too.
- Video thumbnails and real YouTube video URLs (currently placeholder thumbs).
- The "prompt tightener" and similar tools are layout previews only. The AI cost calculator is real and computes live.

## Editing the design

The source of truth is the Claude Design project "Prototype comparison exploration", file `Michaels Corner.dc.html`. To change layout or content, edit it there and re-export `index.html` + `support.js`, or hand-edit `index.html` directly (it is plain HTML with an inline `data-dc-script`).
