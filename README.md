# Santhosh Raj K — Portfolio

A single-page personal portfolio built as a self-contained HTML file, featuring a live 3D neural-network hero (WebGL / Three.js), a scroll-aware nav bar, and interactive 3D tilt on the project cards.

**Live site:** https://yourusername.github.io/ *(update once deployed — see below)*

---

## About

I'm a B.Tech student in Artificial Intelligence and Machine Learning at Panimalar Engineering College, Chennai. This portfolio covers my background, internship experience, projects, and how to get in touch.

- 📍 Chennai, Tamil Nadu, India
- 📧 r.k.santhosh07@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/santhosh-raj-a16081328)

## Features

- **3D neural-network hero** — an animated WebGL node graph (built with [Three.js](https://threejs.org/)) that rotates slowly and responds to mouse/touch movement, echoing the ML theme of the site
- **Interactive project cards** — real 3D tilt on hover using CSS transforms, driven by cursor position
- **Scroll-aware navigation** — nav bar shifts from transparent-over-hero to solid once you scroll past it
- **Fully responsive** — works on mobile, tablet, and desktop
- **Accessible by default** — respects `prefers-reduced-motion` for users who've disabled animations at the OS level
- **Zero build step** — one HTML file, no bundler, no `node_modules`

## Tech stack

| Purpose         | Tool                                   |
|------------------|-----------------------------------------|
| 3D rendering     | [Three.js](https://threejs.org/) (via CDN) |
| Fonts            | Google Fonts — Fraunces, Inter, IBM Plex Mono |
| Everything else  | Vanilla HTML, CSS, and JavaScript |

No frameworks, no package manager, no build tools — the whole site is `index.html`.

## Running locally

No installation needed. Either:

- Double-click `index.html` to open it directly in your browser, **or**
- Serve it locally for the most accurate preview (recommended, since some browsers restrict local file access for fonts/scripts):

```bash
git clone https://github.com/yourusername/yourusername.github.io.git
cd yourusername.github.io
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

## Deployment

This site is deployed with **GitHub Pages**, served directly from the `main` branch. Any push to `main` updates the live site within a minute or two.

To deploy your own copy:
1. Fork or clone this repo
2. Push to a repo named `yourusername.github.io` (for the root URL) or any repo name (served at `/repo-name/`)
3. In the repo, go to **Settings → Pages**, set source to **Deploy from a branch**, choose `main` / `root`, and save

## Structure

```
.
├── index.html    # entire site — markup, styles, and scripts
└── README.md     # this file
```

## Credits

- 3D rendering powered by [Three.js](https://threejs.org/)
- Fonts from [Google Fonts](https://fonts.google.com/)

---

Feel free to fork this as a starting point for your own portfolio — just swap in your own content, colors, and links.
