# GitHub Pages deployment

Upload all three files from this directory to the root of the `rajmohanacharya/ai` repository:

```text
index.html
config.js
.nojekyll
```

Publish from the `main` branch and `/(root)` folder.

Do not place an API key or Cloudflare URL in these files. The current backend is supplied by the signed access link printed in Colab.

The plain URL remains:

```text
https://rajmohanacharya.github.io/ai/
```

For actual access, share the complete `#backend=...&expires=...&sig=...` link printed by the notebook.

The page is self-contained and does not load browser libraries or fonts from third-party CDNs. `config.js` contains no secret; it only controls the offline text, an optional public Notify Raj link, and the status-poll interval.
