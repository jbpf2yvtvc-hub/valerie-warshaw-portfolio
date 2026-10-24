# Valerie Warshaw Portfolio Site

A single static page (`index.html`) with no build step, hosted free on GitHub Pages.

## What's here

- `index.html`: the whole site (layout, styles, and the small image-gallery script)
- `assets/img/`: project images taken from the portfolio PDF. `pNN.jpg` is the full size image and `pNN-sm.jpg` is the smaller grid image; `NN` is the PDF page number.
- `Valerie-Warshaw-Portfolio.pdf`: the downloadable portfolio

## Common edits

- **Bio:** in `index.html`, between `<!-- BIO -->` and `<!-- /BIO -->`
- **Replace the PDF:** upload a new file with the same name, `Valerie-Warshaw-Portfolio.pdf`
- **Projects:** each project is one `<li class="project">` block. The `data-gallery` list holds the images and captions shown when it's clicked.
