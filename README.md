# M10 — Georgia Monjarrez's Quarto Portfolio

## Build

Install Quarto and R with `knitr`, `rmarkdown`, and `ggplot2`.

```sh
quarto render
quarto preview
```

Open `M10.Rproj` to work in RStudio. The four main pages are `index.qmd`, `dashboard.qmd`, `styling.qmd`, and `listings.qmd`. Project entries live in `projects/`; source data and provenance notes live in `data/`. Rendering writes the complete static site to `docs/`.

## Published portfolio

- Website: https://gmonjarrez.github.io/m10-quarto-portfolio/
- Repository: https://github.com/gmonjarrez/m10-quarto-portfolio
- Submission report: `submission.qmd` and `docs/submission.html`

GitHub Pages serves `docs/` from `main`. Render locally and push the updated source and output to update the website. The home page includes the personal photo supplied for this portfolio.

## Data

The dashboard uses documented CEP planning metadata, not observed outcomes. See `data/README.md`. The observation CSV is a blank template. Do not publish identifiable participant information.
