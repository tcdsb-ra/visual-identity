# TCDSB Visual Identity — Brand Definition

This repository defines the TCDSB Research & Analytics visual identity as a [`_brand.yml`](https://quarto.org/docs/authoring/brand.html) file for use with Quarto documents.

## Using in a Project

Add the brand to any Quarto project with:

```bash
quarto use brand tcdsb-ra/visual-identity
```

or in R:

```r
tcdsb::tcdsb_project_setup()
```

This copies `_brand.yml` and the `assets/` directory into your project root. Quarto will automatically apply the brand (colours, fonts, logos) to all supported output formats.

## Contents

- `_brand.yml` — Colour palette, semantic tokens, typography, and logo references
- `assets/` — Logo files (PNG)
