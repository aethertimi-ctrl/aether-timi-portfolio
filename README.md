# Aether Timi — Digital Agency Website

The website for Aether Timi, an AI-assisted digital agency based in Nigeria and working worldwide.
Live at https://aether-timi-portfolio.vercel.app

## What's inside
- `index.html` — the whole site (HTML, CSS and JavaScript in one file, no build step)
- `assets/` — SVG logo set (horizontal dark/light, monochrome, symbol) and favicon
- `og-image.png` — social sharing image (1200×630)
- `404.html`, `robots.txt`, `sitemap.xml`, `vercel.json`

## Features
- Original A+T monogram logo, drawn as vectors
- Futuristic dark design with motion that respects `prefers-reduced-motion`
- Responsive on mobile, tablet and desktop, with keyboard-friendly navigation
- Selected work section featuring projects from GitHub
- Contact form that opens a ready-to-send WhatsApp or email message

## Run locally
Open `index.html` in a browser, or run `python -m http.server 8000` and visit http://localhost:8000.

## Deploy
Pushed to `main`, Vercel deploys it automatically (framework preset: Other, no build command, output directory `.`).

## Adding a live demo to a work card
Each card in the Work section has a "Live demo coming soon" label. Once a project is deployed, replace that
`<span class="soon">` with `<a class="link" href="LIVE_URL" target="_blank" rel="noopener">Live demo ↗</a>`.

## Contact
- WhatsApp: +234 813 934 2375 (https://wa.me/2348139342375)
- Email: Aethertimi@gmail.com
- GitHub: https://github.com/aethertimi-ctrl · X: https://x.com/AetherTimi · LinkedIn: https://www.linkedin.com/in/aether-timi
