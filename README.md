# Anonymous Supplementary Website

Static, dependency-free project page intended for anonymous review.

## GitHub Pages
1. Create a small public repository.
2. Copy these files to the repository root.
3. Add anonymized images/videos under `static/`.
4. Settings -> Pages -> Deploy from a branch -> `main` / `(root)`.
5. In anonymous.4open.science, anonymize the same branch and enable GitHub Pages.

All paths in `index.html` are relative so the page works below `/w/<repository-id>/`.

## Before publishing
- Remove author names, affiliations, emails, lab names, logos, personal links, BibTeX, and analytics.
- Inspect SVG source text and all binary image/video content manually.
- Strip video metadata.
- Open the anonymous URL in a private browser window and inspect page source.
