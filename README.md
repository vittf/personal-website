# personal-website

A simple static personal site (plain HTML + CSS), hosted with GitHub Pages.

## Editing

- **Text**: edit `index.html` — replace every "Your Name" and placeholder text.
- **Photo**: add a square-ish photo as `assets/profile.jpg`. Until then a placeholder is shown.
- **CV**: add your CV as `assets/cv.pdf` — the "Download CV" button links to it.
- **Colours**: change `--accent` in `style.css` (dark-mode values are just below).
- **Favicon**: change the initials in `assets/favicon.svg`.

Preview locally by opening `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.

## Publishing on GitHub Pages

1. Push to GitHub: `git add . && git commit -m "Initial site" && git push -u origin main`
2. On GitHub, open the repo → **Settings → Pages**.
3. Under **Build and deployment**, choose **Source: Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute the site is live at `https://vittf.github.io/personal-website/`.

Tip: if you rename the repo to `vittf.github.io`, the site is served at `https://vittf.github.io/` instead.
