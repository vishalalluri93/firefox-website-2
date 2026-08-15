# Firefox Sports & Resorts — Aman-style site

Static HTML site (the lighter, aman.com-inspired redesign). No build step, no dependencies.

## Files
- `index.html`, `weddings.html`, `corporate.html`, `estate.html`, `sports.html`, `hotel.html`, `contact.html`
- `aman.css` — the single stylesheet
- `assets/img/` — photography
- `.nojekyll` — tells GitHub Pages to serve files as-is

## Deploy on GitHub Pages
1. Create a repo and upload the contents of this folder to the repository **root** (so `index.html` is at the top level).
2. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, Folder = `/ (root)`.
3. Your site goes live at `https://<user>.github.io/<repo>/` in a minute or two.

## Notes
- Fonts (Cormorant Garamond, Mulish) load from Google Fonts via a link in each page's `<head>`. For fully self-hosted fonts, download and reference them locally.
- The muted photo grade is a live CSS filter in `aman.css`; for production you may bake it into the image files.
