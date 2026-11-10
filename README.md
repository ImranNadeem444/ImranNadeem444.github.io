# Imran Nadeem — AI/ML Engineer Portfolio

Static portfolio site (plain HTML, CSS, and JavaScript). No build step and no backend, so it runs directly on GitHub Pages.

## Files
- `index.html` — all content and sections
- `styles.css` — design system, layout, and responsive rules
- `script.js` — mobile navigation, scroll reveal, and footer year
- `assets/favicon.svg` — site icon
- `assets/og-image.png` — social preview image (1200×630)
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Publish to GitHub Pages
1. In the repository `ImranNadeem444/ImranNadeem444.github.io`, replace the site files with the contents of this folder.
2. Commit and push to `main`.
3. In **Settings → Pages**, confirm **Deploy from a branch** with `main` and `/(root)`.
4. The site is served at https://imrannadeem444.github.io/ once the build completes.

## Local preview
Run `python -m http.server 5500` in this folder and open http://localhost:5500.

## Updating content
- Projects, experience, and certificates are plain HTML sections in `index.html`.
- Keep every claim tied to real work. Mark unfinished projects with the existing status tags.
