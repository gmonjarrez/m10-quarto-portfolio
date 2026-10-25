# M10 — Georgia Monjarrez's Quarto Portfolio

## Build

Install Quarto and R with `knitr`, `rmarkdown`, and `ggplot2`.

```sh
quarto render
quarto preview
```

Open `M10.Rproj` to work in RStudio. The four main pages are `index.qmd`, `dashboard.qmd`, `styling.qmd`, and `listings.qmd`. Project entries live in `projects/`; source data and provenance notes live in `data/`. Rendering writes the complete static site to `docs/`.

## Publish with GitHub Pages

Push this project to a GitHub repository. In Settings → Pages, choose Deploy from a branch, branch `main`, folder `/docs`, and save. Include `docs/.nojekyll`. After deployment, replace the two pending entries in `submission.qmd` with the verified website and repository URLs and render again.

## Personalization still needed

The home page includes the personal photo supplied for this portfolio. Confirm the career-direction wording and add exact degree details if desired. No degree completion, graduation date, or participant findings are invented.

## Data

The dashboard uses documented CEP planning metadata, not observed outcomes. See `data/README.md`. The observation CSV is a blank template. Do not publish identifiable participant information.
