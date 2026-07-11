# RajAIAssist Georgia-R favicon update

This package keeps the existing RajAIAssist design and replaces the favicon letterform with a single serif **R** using this font stack:

```css
Georgia, "Times New Roman", "Liberation Serif", serif
```

`Georgia` is the first-choice font in the SVG. The other serif fonts are fallbacks for platforms where Georgia is unavailable.

Upload or replace these files in the root of the `rajmohanacharya/ai` repository:

- `index.html`
- `favicon.svg`
- `favicon-16x16.png`
- `favicon-32x32.png`
- `favicon-48x48.png`
- `favicon.ico`
- `apple-touch-icon.png`
- `android-chrome-192x192.png`
- `favicon-512x512.png`
- `site.webmanifest`
- `rajai-social-preview.webp`

Keep the existing `config.js`, `runtime-endpoint.json`, and `.nojekyll` files.

The favicon references in `index.html` now use `?v=2` to bypass Chrome's old icon cache.

After GitHub Pages redeploys, verify:

- `https://rajmohanacharya.github.io/ai/favicon.svg?v=2`
- `https://rajmohanacharya.github.io/ai/?v=georgia-r2`

Only the favicon letter uses Georgia. The main RajAIAssist interface typography is unchanged.
