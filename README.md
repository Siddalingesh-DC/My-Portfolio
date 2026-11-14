# Siddalingesh DC — Portfolio v2

An immersive, editorial-style portfolio for GitHub Pages. The visual language is intentionally different from the first version: oversized typography, high-contrast acid-lime accents, a conceptual EV systems orbit, interactive system map, animated transitions, project case-study dialogs, filterable capabilities and a responsive layout.

## Publish

1. Extract this ZIP.
2. Upload the **contents** of this folder to the root of your GitHub Pages repository (the `index.html` file must be at repository root).
3. Commit to your publishing branch.
4. Open **Settings → Pages** and select **Deploy from a branch**, branch `main`, folder `/ (root)`.
5. Open the published URL shown by GitHub Pages.

No Node.js, npm install or build step is required.

## Files

- `index.html` — entire portfolio, styles and interactions
- `assets/Siddalingesh_DC_Resume.pdf` — resume download
- `assets/favicon.svg` — browser icon
- `assets/og-cover.svg` — social preview image
- `manifest.webmanifest`, `sw.js` — PWA metadata and offline shell
- `.nojekyll` — disables Jekyll processing

## Before publishing

- Verify the VisionAstraa internship end date; it is displayed at year level (`2025*`) because the exact end date has not been confirmed.
- Add the MBSE course provider and completion year if available.
- Add award years / award programme details if available.
- Add the Learn Things YouTube URL when ready. No unverified URL is included.
- Review the publicly displayed phone number, email and LinkedIn URL.
- Do not publish proprietary station architecture, internal API details, battery limits, customer data, or confidential failure analysis.

## Technical notes

- Built with HTML, CSS and vanilla JavaScript; no framework or build system.
- Interactive system map is conceptual and is not SUN Mobility's actual architecture.
- The contact form prepares a `mailto:` draft; it does not submit to a server or store messages.
- Motion responds to `prefers-reduced-motion`; the layout and interactions are keyboard-friendly.
- Google Fonts are loaded externally with system fallbacks.
- Service worker is registered only when served over HTTP/HTTPS (GitHub Pages qualifies).
- The portfolio does not claim unprovided performance metrics or tool proficiency percentages.
