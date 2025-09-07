# AlignID — quick photo resizing for IDs & passports

AlignID is a simple, client-side web tool that helps you crop and resize photos to common ID and passport specifications. It runs entirely in your browser—no sign-in, no uploads.

> ⚠️ Always verify your country’s official photo rules (size, DPI, background, head size, glasses, etc.). AlignID is a helper tool, not legal advice or an official validator.

---

## Features
- Presets for common ID/passport sizes (e.g., 2×2 in / 35×45 mm).
- Smart crop with alignment grid and safe-zone guides.
- Background fill (solid color) and quick margins.
- One-click export (PNG/JPG).
- 100% local processing (privacy-friendly).

---

## Live demo
- **GitHub Pages:** _enable Pages on the repo and the link will go here_
- Local file: just open `align_id.html` in your browser (see “Run locally”).

---

## Screenshot
Add a screenshot to `docs/screenshot.png` (create the folder if needed), then it will be shown here:

![AlignID screenshot](docs/screenshot.png)

---

## Run locally

### Option A — Double-click
1. Clone or download this repo.
2. Double-click `align_id.html` to open it in your default browser.

> If your browser blocks local file access for some features, try Option B.

### Option B — Simple HTTP server
Use any quick static server you like:

**Python 3**
```bash
cd path/to/AlignID
python -m http.server 5173
# open http://localhost:5173/align_id.html
