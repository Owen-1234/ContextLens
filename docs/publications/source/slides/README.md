# ContextLens AAAI-27 LaTeX Slides

This directory contains the final revised Beamer project. The deck uses:

- Metropolis theme, 16:9
- Duke Royal Blue frame titles and progress bar
- white canvas, Soft Blue callout boxes

Compile from this directory with:

```bash
latexmk -xelatex -outdir=build main.tex
```

The compiled presentation is `build/main.pdf`. The repository delivery copy is
[`../../contextlens-aaai27-slides.pdf`](../../contextlens-aaai27-slides.pdf).

## Overleaf

1. Choose **New Project → Upload Project** and upload the provided ZIP file.
2. Open **Menu → Settings → Compiler** and select **XeLaTeX**.
3. Keep `main.tex` as the main document, then click **Recompile**.

All figures, title icons, team images, and bibliography sources required by the
deck are included here and referenced with relative paths.
