# Excalibur — Księga zasad

Rulebook for the board game **Excalibur**, rendered as static HTML.

**Read online:** https://fkowal.github.io/excalibur/

| Language | HTML | PDF |
|---|---|---|
| Polski (default) | [index.html](https://fkowal.github.io/excalibur/) | [excalibur-pl.pdf](downloads/excalibur-pl.pdf) |
| English | [en.html](https://fkowal.github.io/excalibur/en.html) | [excalibur-en.pdf](downloads/excalibur-en.pdf) |

## Layout

```
index.html        Polish rulebook (site default)
en.html           English rulebook
img/              figures used by both HTML versions
downloads/        print-ready PDFs
excalibur-pl.html redirect to / (keeps the old filename working)
404.html          GitHub Pages not-found page
.nojekyll         serve files as-is, skip Jekyll
```

## Publishing

Served by GitHub Pages from the `main` branch, root folder. Any push to `main` redeploys the site.

Pages are laid out as A4 sheets — use the browser's *Print → Save as PDF* to regenerate the PDFs.
