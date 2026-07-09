# A Field Guide to the Solar System 🪐

A single-page, animated field guide to the eight planets (plus Pluto) — built as a scroll-driven journey outward from the Sun, with a live canvas starfield, an interactive orbital nav, and real facts about each world.

**Live demo:**  https://laiba-shaban.github.io/A-Field-Guide-to-the-Solar-System/

## Description

Instead of a static list of planet facts, this project treats the solar system as a scroll narrative: each planet gets its own section with a glowing, shaded sphere, a distance-from-the-Sun tag, quick facts, and a "field note" aside with a fun, lesser-known detail. A small animated orrery in the corner doubles as navigation — click any orbiting dot to jump straight to that planet, and it lights up automatically as you scroll past each section.

## Features

- 🌌 Canvas-based starfield background with twinkling stars and an occasional comet streak
- 🛰️ Animated orrery navigation (hero + fixed corner widget) with planets actually orbiting in real time
- 🪐 Nine planet sections (Mercury → Neptune, plus Pluto) with shaded, glowing CSS spheres and real specular highlights
- 🎨 Per-planet ambient color wash and glass-style fact pills
- 📱 Fully responsive, down to mobile
- ♿ Respects `prefers-reduced-motion`

## Tech Stack

- **HTML5** — structure and content
- **CSS3** — gradients, animations, backdrop blur, responsive layout (no framework)
- **Vanilla JavaScript** — Canvas API (starfield/comet), SVG (orrery), IntersectionObserver (scroll reveals + active-section nav highlighting)
- **Google Fonts** — Space Grotesk, Inter, JetBrains Mono

No build step, no dependencies, no frameworks — it's a single static HTML file.

## Project Structure

```
solar-field-guide/
└── index.html   # everything — markup, styles, and script — in one file
```
