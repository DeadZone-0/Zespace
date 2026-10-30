# ze's site

A lightweight, zero-telemetry personal portfolio and thought-dump space styled with an energetic, hand-inked lineart aesthetic.


**[Explore Live Demo →](https://deadzone-0.github.io/ze-portfolio/)**

---

## Features

- **Hand-Inked Pen Lineart**: Organic multi-stroke contours with spiky corner overshoots that avoid rigid CSS box-model rectangles.
- **Stop-Motion Line-Boil**: Subtle, living pen tremor running natively at 3–4 FPS to mimic analog indie-animation and sketch cuts.
- **Two-Column Bento Layout**: Clean separation between social channels and the project catalog (`/projects`, `/setup`, `/aboutme`).
- **Torn-Paper Scraps Drawer**: Slide-out notebook sheet pulling out from the screen edge with distinct tabs for dev blogs, unvarnished 3am thoughts, and live system clocks.
- **Zero Telemetry & Zero Bloat**: No analytics trackers, no advertising beacons, and no heavy runtime dependencies.

## Quick Start (Run Locally)

No Node.js, bundlers, or package installations required. Clone and serve with Python:

```bash
git clone https://github.com/DeadZone-0/ze-portfolio.git
cd ze-portfolio
python3 -m http.server 8000
```

Open `http://localhost:8000` in your browser.

## How It Works

- **Stop-Motion Jitter via Step-Interpolation**: Instead of burning CPU with JavaScript requestAnimationFrame canvas loops, the wobbly pen jitter uses native CSS `@keyframes` with `steps(3, end)` timing. This creates a jerky, hand-drawn 3-frame animation cut while keeping CPU usage near zero.
- **Multi-Pass SVG Stroke Outlines**: Rather than standard `border-radius`, interactive buttons and panels use layered SVG stroke paths with randomized corner overshoots and crossing slash lines. On hover, elements invert into dense ink-scratched crosshatching.
- **Zero Build-Step Architecture**: The entire site is authored in standard vanilla HTML5 and CSS3, making it instantly portable, archivable, and deployable to GitHub Pages with zero compilation lag.

## Credits

- Typefaces: [Caveat](https://fonts.google.com/specimen/Caveat) and [Patrick Hand](https://fonts.google.com/specimen/Patrick+Hand) via Google Fonts
- Icons: [Font Awesome](https://fontawesome.com/)
- Author: [Ze (@DeadZone-0)](https://github.com/DeadZone-0)
