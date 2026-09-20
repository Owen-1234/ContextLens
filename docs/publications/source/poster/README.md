# ContextLens AAAI-27 A0 Poster — Overleaf package

This folder is a self-contained LaTeX project for an **A0 portrait** academic poster.

## Overleaf

1. Upload the ZIP file as a new Overleaf project.
2. Open **Menu → Compiler** and select **XeLaTeX**.
3. Set `main.tex` as the main document if Overleaf does not select it automatically.
4. Click **Recompile**.

`main.tex` generates the poster directly with LaTeX and `beamerposter`. It does not include or depend on a pre-rendered poster PDF. The title, author block, three-column layout, metric summaries, timeline, captions, and references are native LaTeX elements.

All five source figures are stored in `figures/`. The GitHub QR code is generated natively by the LaTeX `qrcode` package and points to `https://github.com/Owen-1234/ContextLens`. The project uses no external logo and no local absolute path. The compiled page size is A0 portrait, 841 × 1189 mm.
