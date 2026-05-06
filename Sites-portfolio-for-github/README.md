# Portfolio Website

This is a simple, responsive portfolio site with three pages:

- Home (`index.html`)
- Résumé (`resume.html`) — embeds a PDF
- Samples (`samples.html`)

## Open it

You can open `index.html` directly in a browser (double-click in Finder), or use a local server (recommended so PDF embedding is consistent).

### Option A: Ruby local server (works on your setup)

From Terminal:

```bash
cd "/Users/Rory/Sites/portfolio"
ruby -run -e httpd . -p 5173
```

Then visit `http://localhost:5173/index.html`.

### Option B: macOS built-in Python server (if available)

From Terminal:

```bash
cd "/Users/Rory/Sites/portfolio"
python3 -m http.server 5173
```

Then visit `http://localhost:5173`.

## Customize

- **Your name / about text**: edit `index.html`
- **Headshot**: replace `assets/headshot.png` with your own image (PNG/JPG) and keep the filename, or update the `src` in `index.html`.
- **Résumé PDF**: replace `assets/resume.pdf` with your real résumé PDF (keep the filename).

