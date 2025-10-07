# AlignID — quick photo resizing for IDs & passports

![Built with](https://img.shields.io/badge/Built%20with-HTML%20%7C%20CSS%20%7C%20JS-blue)
![Privacy](https://img.shields.io/badge/Privacy-100%25%20local-informational)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

AlignID is a simple, client-side web tool that helps you crop and resize photos to common ID and passport specifications. It runs entirely in your browser—no sign-in, no uploads.

>  **Always verify your country’s official photo rules** (size, DPI, background, head size, glasses, etc.). AlignID is a helper tool, not legal advice or an official validator.

[🌐 Live Demo](#-live-demo) · [📸 How to Use](#-how-to-use) · [🔧 Run Locally](#-run-locally) · [🚀 Deploy](#-deploy-to-github-pages) · [❓FAQ](#-faq)

---

##  Features
- **Presets** for common ID/passport sizes (e.g., **2×2 in** / **35×45 mm**).
- **Smart crop** with alignment grid + “safe-zone” guides.
- **Background fill** (solid color) and quick margins.
- **One-click export** (**PNG/JPG**) with selectable **DPI** (e.g., 300).
- **100% local** processing (privacy-friendly).

---

## 🖥 Live demo
- **GitHub Pages:** _add your link here once Pages is enabled_
- **Local file:** open `align_id.html` in your browser (see **Run locally** below)

---

##  How to Use
1. Click **Upload** and choose your photo (high-resolution is best).
2. Pick a **Preset** (e.g., *US 2×2 in*, *EU 35×45 mm*).
3. Drag the image to **align the head** within the safe-zone guides.
4. Optional:
   - Change **background color** (e.g., white) or tweak **margins**.
   - Set **DPI** (usually **300 DPI** for print).
5. Click **Export** → choose **PNG** or **JPG** → your file downloads.

> Tip: for printing at home, use the **300 DPI** option and check printer scaling is **100%** (no “Fit to page”).

---

##  Tech Stack
- **Vanilla** HTML, CSS, and JavaScript
- **Canvas** for crop/resize and export
- No server, no frameworks required

---

## 🔧 Run Locally

### Option A — double-click
- Just double-click `align_id.html` (works in all modern browsers).

### Option B — simple static server (recommended)
This avoids any browser security warnings with local files.

**Windows (PowerShell):**
```powershell
# from the project folder
python -m http.server 5173
# then open http://localhost:5173/align_id.html
