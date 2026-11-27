# LAB READY — Infectious Diseases Reference

A responsive, installable, offline-ready PWA prototype for clinical infectious diseases and diagnostic microbiology. It includes searchable educational reference cards covering specimen collection, blood-culture workflows, AST interpretation principles, antibiotic-class overviews, antimicrobial resistance, stewardship, and clinical review checklists.

## Run locally

Serve this directory over HTTP (service workers do not work from `file://`). For example, with Python installed:

```bash
python -m http.server 8000
```

Then open http://localhost:8000. On a hosted HTTPS site, the app can be installed from a compatible browser and its core pages are cached for offline use.

## Important clinical-use notice

This is an educational prototype, not a medical device or patient-care decision tool. It does not provide patient-specific diagnosis, drug selection, or dosing. It intentionally does not reproduce CLSI tables or breakpoint data. Confirm all decisions against the current CLSI M100 edition, local antibiograms and institutional protocols, current drug labeling, and qualified clinical, pharmacy, and microbiology expertise. In urgent situations, follow local emergency procedures without delay.

## Contents

- `index.html` — app shell
- `app.js` — reference topics, search, navigation, and install prompt
- `styles.css` — responsive UI
- `manifest.webmanifest`, `sw.js`, `icon.svg` — PWA installation and offline cache

The existing ZIP archive in this repository is retained as the original project artifact. No API key or external AI service is required by this prototype.
