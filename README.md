# Tcdsb-visual-identity Extension For Quarto

This extension sets the colours and fonts for Quarto documents to the TCDSB visual identity

## Installing

In an existing project

```bash
quarto add tcdsb-ra/visual-identity
```

or in R:

```r
tcdsb::tcdsb_project_setup()
```

This will install the extension under the `_extensions` subdirectory.
If you're using version control, you will want to check in this directory.

New projects created with the template will automatically receive it. 

## Using

This extension installs a [brand.yml](https://posit-dev.github.io/brand-yml/) configuration for tcdsb.

## Example

Here is the source code for a minimal example: [example.qmd](example.qmd).

