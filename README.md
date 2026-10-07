# Jenan's lecture library

A public download page for six revised Applied Sustainability in Business and Management lectures.

**Website:** https://jalalhussein1982.github.io/jenan-sustainability-lectures/

Each lecture has an editable PowerPoint and its matching lecturer guide PDF. PDFs contain teaching notes, activities, questions and answers; they are not exports of the slides.

The collection combines the final Lecture 1 design (18 September 2026) with the revised Lectures 2–6 (5 October 2026). Files were verified on 7 October 2026. Lecture 1 has 47 slides; Lecture 2 has 35 and covers different content.

## Files

- `index.html` and `styles.css`: responsive download interface, works without JavaScript.
- `files/`: six PPTX/PDF pairs plus a complete ZIP. Individual downloads use consistent lecture numbers. The ZIP preserves the descriptive filenames of the verified source collection.
- `manifest.json`: exact file sizes and SHA-256 checksums.
- `.nojekyll`: publish the static site directly with GitHub Pages.

## Local preview

Run `python3 -m http.server 8765` from this folder, then open http://localhost:8765.

## Updating

Replace the intended lecture's PowerPoint and matching guide together. Update the displayed revision, sizes, counts and manifest checksums, then rebuild the complete ZIP. Preserve the numbered download paths to keep existing links working. GitHub Pages publishes the `main` branch root.

Materials retain their existing authorship and embedded source credits. No additional content license is granted by this repository.
