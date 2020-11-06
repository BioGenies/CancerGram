---
output:
  pdf_document: default
  html_document: default
---
## Test environments

* GitHub Actions (ubuntu-20.04): release, devel
* GitHub Actions (windows): release
* Github Actions (macOS): release

## Additional information for CRAN

This package, similarly to our other tools (https://CRAN.R-project.org/package=AmpGram), this package uses an external GitHub package with a model (https://github.com/BioGenies/CancerGramModel). We are not using the Additional_repositories field as there is no CRAN style repository in that location and hence the declaration won't have any effect anyway (thanks to Uwe Ligges for clarification).

The package is quite verbose, but it can be silenced using `r options(CancerGram_suppress_prompt = FALSE)`.
