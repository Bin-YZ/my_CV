# Bin Xi personal website (Quarto) – v2 redesign

Source files: `_quarto.yml`, `styles.css`, `index.qmd`, and the `news/`, `about/`, `research/`, `publications/`, `teaching/` folders.
Rendered site (ready to upload): `_site/`.

- Preview / rebuild: install Quarto (https://quarto.org), then run `quarto preview` or `quarto render` in this folder.
- Add a publication: append an entry to `publications/publications.yml` (optional fields `doi:` and `pdf:` add DOI/pdf badges).
- Add news: edit the "Latest news" list in `index.qmd`.
- Deploy: push this folder to a GitHub repo and run `quarto publish gh-pages`, or upload the `_site/` folder to any static host (GitHub Pages, Netlify).
