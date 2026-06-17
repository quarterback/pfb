# Portland Futures Bureau

A one-page placeholder site for the Portland Futures Bureau — a civic
laboratory focused on expanding what Portland imagines is possible.

Static HTML + CSS. No build step. Open `index.html` or serve the folder.

## Fonts
- **Wordmark:** [Pally](https://www.fontshare.com/fonts/pally) (Fontshare),
  self-hosted as a variable `.woff2` in `fonts/`.
- **Headings & body:** [Cabinet Grotesk](https://www.fontshare.com/fonts/cabinet-grotesk)
  (Fontshare), loaded from the Fontshare CDN.

## Accessibility
Built to WCAG 2.1 AA:
- Reading text clears 4.5:1 contrast; large display text clears 3:1.
- Color is reinforced by shape, weight and highlight — never the sole signal.
- Skip link, visible `:focus-visible` rings, semantic landmarks/headings.
- Honors `prefers-reduced-motion` and `forced-colors`.

## Structure
```
index.html        # markup + copy
styles.css        # design tokens, color system, layout
fonts/            # Pally variable woff2 (wordmark)
```
