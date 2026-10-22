# lukashaussmann.github.io

Personal research page. Plain static HTML, no build step.

- `index.html` – all content (bio, projects, publications). Search for `TODO`.
- `style.css` – colors are in `:root` at the top (`--accent` is the copper).
- `assets/` – teaser images, CV pdf, photo.

Preview locally: `python3 -m http.server` → http://localhost:8000

Deploy: push to `github.com/LukasHaussmann/lukashaussmann.github.io`, then
Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/`.
