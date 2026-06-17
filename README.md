# NeonForge ⚡

> Beautiful neon button components for dark interfaces. Pure CSS, zero dependencies, copy-paste ready.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-neonforge-7b61ff?style=flat-square)](https://rintuchowdory.github.io/neon-buttons-)
[![License: MIT](https://img.shields.io/badge/License-MIT-0088ff?style=flat-square)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/rintuchowdory/neon-buttons-?style=flat-square&color=00ffaa)](https://github.com/rintuchowdory/neon-buttons-)

---

## Demo

Open `index.html` in a browser or visit the live GitHub Pages site.

Features:
- **Gallery** — 7 color themes with default + pulse variants
- **Custom Builder** — live sliders for glow, intensity, radius, padding
- **One-click CSS copy** — grab any style and drop it into your project

---

## Usage

### 1. Include a button CSS file

```html
<link rel="stylesheet" href="buttons/blue.css" />
```

Or include all of them:

```html
<link rel="stylesheet" href="buttons/blue.css" />
<link rel="stylesheet" href="buttons/green.css" />
<link rel="stylesheet" href="buttons/pink.css" />
<link rel="stylesheet" href="buttons/amber.css" />
<link rel="stylesheet" href="buttons/purple.css" />
<link rel="stylesheet" href="buttons/cyan.css" />
<link rel="stylesheet" href="buttons/red.css" />
```

### 2. Add the class to any button or anchor

```html
<button class="neon-blue">Click Me</button>
<button class="neon-green">Get Started</button>
<button class="neon-pink">Subscribe</button>
<button class="neon-purple">Explore</button>
<button class="neon-cyan">Download</button>
<button class="neon-amber">Purchase</button>
<button class="neon-red">Delete</button>
```

### 3. Add the pulse animation (optional)

```html
<button class="neon-blue neon-pulse">Pulsing</button>
```

---

## Available themes

| Class | Color | Hex |
|-------|-------|-----|
| `.neon-blue` | Blue | `#0088ff` |
| `.neon-green` | Green | `#00ffaa` |
| `.neon-pink` | Pink | `#ff00cc` |
| `.neon-amber` | Amber | `#ffaa00` |
| `.neon-purple` | Purple | `#aa00ff` |
| `.neon-cyan` | Cyan | `#00eeff` |
| `.neon-red` | Red | `#ff2244` |

---

## Custom builder

Open the **Builder** section in `index.html` to:

- Pick any color with the swatch picker or color input
- Adjust glow size, intensity, border width, radius, and padding
- Toggle pulse animation and fill-on-hover
- Copy the generated CSS instantly

---

## File structure

```
neon-buttons-/
├── index.html          ← full interactive playground
├── style.css           ← page layout and UI styles
├── app.js              ← builder logic and copy helpers
├── buttons/
│   ├── blue.css
│   ├── green.css
│   ├── pink.css
│   ├── amber.css
│   ├── purple.css
│   ├── cyan.css
│   └── red.css
└── README.md
```

---

## Deploy to GitHub Pages

```bash
git add .
git commit -m "feat: NeonForge rebuild"
git push origin main
```

Then go to: **Settings → Pages → Source → main / (root)** and save.

Your site will be live at:
`https://rintuchowdory.github.io/neon-buttons-`

---

## License

MIT — free to use in personal and commercial projects.

---

Made by [rintuchowdory](https://github.com/rintuchowdory)
