# Portfolio — Mohamed Amine Ben Belgacem

Static, responsive bilingual (FR/EN) portfolio built from the supplied CV. No build tool or dependency is required.

## Run locally

From this folder:

```bash
python3 -m http.server 4173
```

Open `http://localhost:4173`.

## Publish cheaply / free

1. **GitHub Pages** — free for a public repository, simple for this static site. Upload the contents of this folder, then enable Pages from the repository settings.
2. **Cloudflare Pages** — free tier, good global performance and custom-domain support. Connect a Git repository and set the build output folder to the repository root (no build command).
3. **Netlify** — free tier, deploy by dragging this folder or connecting Git. No build command is needed.

## Image attribution and scope

The Promovacances image is a public App Store screenshot supplied from its Apple App Store listing. The source links for Promovacances, FRAM, Carrefour and Amen Mobile are present in the site’s “Note sur les visuels” section. Product imagery is solely contextual; it does not claim ownership, endorsement, or authorship beyond the factual CV statements.

## Files

- `index.html` — structure and bilingual copy hooks
- `styles.css` — responsive presentation
- `script.js` — FR/EN toggle, reveal effects and email-copy interaction
