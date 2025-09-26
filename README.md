Blockchain Developer Portfolio — local preview and notes

Overview

This is a single-file portfolio site located at `Portfolio_website.html`. It includes:

- Animated hero with a floating gradient blob.
- Typewriter subtitle effect.
- Projects grid with SVG thumbnails and interactive cards.
- Modal panel with project details, tech tags, and screenshot support (WebP preferred, PNG fallback).
- Accessibility and keyboard support (ARIA attributes, Enter/Space activation, Esc to close modal).
- Reveal-on-scroll and subtle tilt interactions (tilt disabled on touch devices).

How to preview locally

Option A — Open file directly (quickest):

1. In File Explorer, double-click `Portfolio_website.html`.
2. Or run from PowerShell:

```powershell
Start-Process -FilePath "C:\Users\leeda\Desktop\Blockchain Portfolio\Portfolio_website.html"
```

Option B — Start a simple local server (recommended for accurate network/resource behavior):

```powershell
cd "C:\Users\leeda\Desktop\Blockchain Portfolio"
python -m http.server 8000
# Then open in browser: http://localhost:8000/Portfolio_website.html
```

Files to add for screenshots (optional)

If you want project screenshots to appear in the modal, place files in an `images/` folder next to `Portfolio_website.html` with these base names (JS will try `.webp` then `.png`):

- `images/voting.webp` (or `voting.png`)
- `images/auction.webp` (or `auction.png`)
- `images/scanner.webp` (or `scanner.png`)

If you prefer, I can optimize and convert PNGs you upload to webp and generate responsive sizes.

Validation & testing performed

- Static HTML/JS checks: no syntax errors reported for the edited file.
- Manual smoke test recommended: open the page, verify modal opens, typewriter runs, cards reveal while scrolling, and keyboard interactions work.




