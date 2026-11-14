# Siddalingesh DC — Portfolio V3

A bespoke, responsive, no-build portfolio for GitHub Pages. Design direction: **Engineering Field Journal** — an editorial systems-engineering portfolio with a warm technical-paper aesthetic, a deep-green system visual, diagram-led storytelling and detailed interactive case studies.

## Publish to GitHub Pages

1. Download and extract the ZIP package.
2. Open the existing portfolio repository on GitHub.
3. Replace the publishing-root `index.html` with this package's `index.html`.
4. Replace `sw.js` and `manifest.webmanifest`.
5. Upload/replace the complete `assets/` directory.
6. Commit to the branch and folder configured under **Settings → Pages**.
7. Wait until the Pages deployment completes, then hard-refresh (`Ctrl + Shift + R`).

`index.html` must be directly inside the configured publishing root (usually repository root or `/docs`), not inside an extra nested folder.

## Files

```text
repository-root/
  index.html
  manifest.webmanifest
  sw.js
  assets/
    favicon.svg
    og-cover.svg
    Siddalingesh_DC_Resume.pdf
```

## Included interactions

- Sticky responsive navigation, mobile menu and reading progress bar
- Light/dark colour mode
- Progressive scroll reveal (content remains visible when scripts fail or reduced motion is enabled)
- Clickable conceptual EV system map with contextual detail panel
- Six expandable project case studies
- Capability explorer with category tabs
- Resume download and email / phone / LinkedIn contact links
- Service worker with versioned cache and network-first navigation

## Content notes to verify before publishing

- Confirm the exact end month for the VisionAstraa EV Academy internship. The timeline currently shows `NOV 2024 — 2025` because the precise end month was not provided.
- Add the official URL for the **Learn Things** channel when available. No channel URL has been assumed.
- Consider adding measurable, non-confidential outcomes to case studies (for example, test-case count, number of charger variants or a verified fault-ticket reduction) only when you can substantiate them.
- Review personal phone/email visibility before publishing the repository publicly.

## Confidentiality

The station ecosystem graphic and project descriptions are conceptual and generalised. Do not publish confidential station architecture, APIs, internal protocols, battery limits, source code, detailed operational data or proprietary implementation diagrams.

## Technical notes

- No npm, bundler, framework, server or build step is required.
- Google Fonts are progressive enhancements; system fallbacks are defined.
- JavaScript is used for interactions only. Core content remains in HTML and visible if JavaScript fails.
- Contact actions use `mailto:` / `tel:`; no backend form storage is implied.
