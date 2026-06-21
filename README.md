# Visit Sambalpur — Hometown Homepage

**[Live Demo](https://sspatel107.github.io/hometown-homepage/)**

A small responsive homepage celebrating **Sambalpur**, a city in western Odisha, India.
Built from scratch with HTML and CSS as a Scrimba-style hometown project.

## Sections

1. **Hero** — a full-bleed background photo (sunset over Hirakud Dam from Gandhi Minar)
   with a translucent banner introducing the city.
2. **Top three things to do** — a flexbox row of three circular highlights:
   - Maa Samaleswari Temple
   - Hirakud Dam
   - Gangadhar Meher University

## Requirements covered

- **Classes** — all styling is driven by class selectors (BEM-style naming).
- **Flexbox** — used to center the card, lay out the activities row, and stack on mobile.
- **Background-image** — the hero uses a `background-image` with a gradient overlay.
- **Color palette** — defined as CSS custom properties in `:root` to match the mockup.

## Extra touches

- Hover effects: image zoom, card lift, banner raise, and a subtle hero background zoom.
- Smooth transitions on all interactive elements.
- Mobile-first responsive layout (columns stack under 600px).

## Project structure

```
hometown-homepage/
├── index.html
├── styles.css
├── README.md
└── images/
    ├── hero.png        # Hirakud Dam sunset (Gandhi Minar)
    ├── temple.png      # Maa Samaleswari Temple
    ├── dam.png         # Hirakud Dam aerial
    └── university.png  # Gangadhar Meher University gate
```

## How to view

Open `index.html` in any web browser.
