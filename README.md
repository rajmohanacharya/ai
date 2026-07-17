# RajAIAssist GitHub Pages v3.1.1

Upload this directory's contents to the root of `rajmohanacharya/ai`.

Public routes:

- `/ai/` — main RajAIAssist workspace.
- `/ai/howto/` — generated public User Guide and advanced prompt library.
- `/ai/howtoadmin/` — owner-authentication shell only.
- `/ai/help/public-help-index.json` — generated public help retrieval index.

The GitHub Pages directory does not contain the Administrator Manual body. The actual manual is packaged inside the CLI wheel and served only by the owner-authenticated backend.

v3.1.1 includes:

- Lustro dark glass and fully light Apple themes;
- 1K/2K/4K/8K output selection;
- Balanced and Conservative visible response controls;
- runtime, context, output, elapsed, and compute badges;
- clipboard screenshot OCR and multiple-file ingest;
- Continue response action;
- strict owner/guest capability rendering;
- owner-only Local-First Vault controls;
- role-aware Guides card;
- public help index and protected admin shell.

When a runtime is online, preserve its current `runtime-endpoint.json` or run `rajai-colab repair` immediately after deployment.
