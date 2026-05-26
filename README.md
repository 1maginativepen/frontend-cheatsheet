# Cheat // Sheet

> A single-file frontend reference for developers — layouts, flexbox, grid, selectors, animations, units, and more. No frameworks, no build step, no dependencies.

![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen?style=flat-square)
![Single File](https://img.shields.io/badge/single-file-blueviolet?style=flat-square)

---

## What's inside

12 reference sections, all in one `cheatsheet.html` file you can open locally or deploy anywhere.

| # | Section | Type |
|---|---------|------|
| 01 | **Layout Playground** — Fluid, Grid, Holy Grail, Cards across Web / Tablet / Mobile | Interactive |
| 02 | **Box Model** — Visual diagram + property table + code snippet | Reference |
| 03 | **Flexbox** — Live demo with controls, container & item property tables | Interactive |
| 04 | **CSS Selectors** — Full table, specificity meter, pseudo-class demo | Interactive |
| 05 | **Typography** — Type scale, key properties, fluid `clamp()` guide | Reference |
| 06 | **Colors** — All formats: hex, rgb, hsl, oklch, color-mix, currentColor | Reference |
| 07 | **Breakpoints** — Visual track, mobile-first vs. container queries | Reference |
| 08 | **Positioning & Z-Index** — All 5 values + visual z-index stack | Reference |
| 09 | **Animations & Transitions** — 6 live animations + `@keyframes` examples | Interactive |
| 10 | **CSS Units** — px, rem, em, %, vw, vh, dvh, ch, fr, clamp + when to use each | Reference |
| 11 | **CSS Custom Properties** — Patterns, JS integration, design token guide | Reference |
| 12 | **CSS Grid** — Container & item properties, auto-fit responsive pattern | Reference |

---

## Usage

**Option 1 — Open directly**
```bash
# Clone and open
git clone https://github.com/your-username/cheatsheet.git
open cheatsheet.html
```

**Option 2 — Deploy to GitHub Pages**
1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your cheatsheet is live at `https://your-username.github.io/cheatsheet`

**Option 3 — Just download**

[Download cheatsheet.html](./cheatsheet.html) and open it in any browser. That's it.

---

## Features

- **Zero dependencies** — one HTML file, no npm, no build step
- **Dark theme** — easy on the eyes for long reference sessions
- **Interactive controls** — toggle layouts, viewports, flex properties live
- **Copy buttons** — grab any code snippet instantly
- **Sticky nav** — jump to any section quickly
- **Fully self-contained** — fonts load from Google Fonts; everything else is inline

---

## Screenshots

### Layout Playground
Toggle between Web / Tablet / Mobile views and switch layout types (Fluid, CSS Grid, Holy Grail, Cards). The HTML and CSS code updates live.

### Flexbox Demo
Adjust `justify-content`, `align-items`, `flex-direction`, and `flex-wrap` interactively — the generated CSS is shown below the demo.

### Specificity Meter
Visual bar chart comparing selector specificity, with an interactive pseudo-class hover demo.

---

## Sections at a glance

```
cheatsheet.html
│
├── 01  Layout Playground     (4 layouts × 3 viewports, live code)
├── 02  Box Model             (visual diagram, property reference)
├── 03  Flexbox               (interactive live demo)
├── 04  CSS Selectors         (table, specificity, pseudo-classes)
├── 05  Typography            (scale, clamp(), key properties)
├── 06  Colors                (all formats, modern oklch)
├── 07  Breakpoints           (visual track, container queries)
├── 08  Positioning           (all values, z-index scale)
├── 09  Animations            (6 live demos, @keyframes, transition)
├── 10  Units                 (all units, when-to-use guide)
├── 11  CSS Custom Properties (patterns, JS, design tokens)
└── 12  CSS Grid              (full reference, auto-fit pattern)
```

---

## Contributing

Found a missing property, outdated technique, or want to add a section?

1. Fork the repo
2. Edit `cheatsheet.html` directly
3. Open a PR with a short description of what you added or fixed

All sections live in clearly commented blocks inside the single file — easy to navigate.

---

## License

MIT — use it, fork it, share it, build on it.
