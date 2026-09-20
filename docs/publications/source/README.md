# LaTeX Sources

These directories reproduce the browser-viewable publication files one level
above:

- [`paper/`](paper/) - AAAI-27 demo paper; compile `main.tex` with `latexmk -pdf`.
- [`supplement/`](supplement/) - technical supplement; compile `main.tex` with `latexmk -pdf`.
- [`poster/`](poster/) - A0 poster; follow the compiler note in its README.
- [`slides/`](slides/) - 16:9 Beamer deck; compile `main.tex` with `latexmk -xelatex`.

Run each command from its source directory so the relative figure and
bibliography paths resolve correctly. Generated build files are intentionally
excluded from version control; the corresponding PDFs are stored in
[`docs/publications/`](../).
