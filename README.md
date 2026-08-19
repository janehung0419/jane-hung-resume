# Jane Hung — Resume

Interview-ready single-page resume site. Bilingual (中文 / English), print-to-PDF friendly, self-contained (no build step, no external JS libraries).

- Live site: https://EasonSu223.github.io/jane-hung-resume/
- Source of truth for content: `index.html` (data for the full project ledger lives inline in a `<script>` block near the bottom of the file).

## Editing

Open `index.html` directly — every bilingual string is a `<span class="zh">…</span><span class="en">…</span>` pair; edit the text inside the relevant span.

Still to fill in:
- `#education` section (currently a placeholder card)
- Phone / location, if you decide to publish them (currently omitted by design)

## Deploy

This repo is served via GitHub Pages from the `main` branch, root folder. Pushing to `main` redeploys automatically.
