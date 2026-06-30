# Portfolio — Chris McAndrew

A static, single-page portfolio: *problem to solution, on repeat*. Five shipped
projects, framed around execution, process, and technical problem-solving.

**Live:** https://cbmca.github.io/portfolio/

## Featured projects
- **Always Early** — Manifest V3 Chrome extension that auto-opens meeting tabs (live on the Chrome Web Store)
- **Stathlon** — iOS live scoring, streaming, and highlights for underserved youth sports (live on the App Store)
- **GeoProwl** — browser arcade of educational games; LLM-generated daily challenge from real data.gov data
- **Clipping API** — ffmpeg-on-Lambda micro-service that cuts branded highlight clips
- **Search Pulse** — turns Google Search Console data into ranked SEO recommendations

## Stack
Plain HTML/CSS/JS — no build step, no dependencies. Fonts via Google Fonts;
reveal-on-scroll via a small `IntersectionObserver` in `script.js`.

## Local preview
Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploy
Hosted on GitHub Pages from the `main` branch (root). `.nojekyll` disables
Jekyll processing. To use a custom domain, add a `CNAME` file with the domain
and point DNS at GitHub Pages.
