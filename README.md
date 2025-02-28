
<!-- README.md is generated from README.Rmd. Please edit that file -->

# scenes <a href="https://r4ds.github.io/scenes/"><img src="man/figures/logo.svg" align="right" height="424" /></a>

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/scenes)](https://CRAN.R-project.org/package=scenes)
[![Codecov test
coverage](https://codecov.io/gh/r4ds/scenes/branch/main/graph/badge.svg)](https://app.codecov.io/gh/r4ds/scenes?branch=main)
[![R-CMD-check](https://github.com/r4ds/scenes/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/r4ds/scenes/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of {scenes} is to make it easy to switch a {shiny} app between
alternative UIs. It was designed to abstract the login-wrapper concept
implemented in [{shinyslack}](https://github.com/r4ds/shinyslack).

## Installation

You can install the development version of scenes from
[GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("r4ds/scenes")
```

## Use Cases

Add at least a short description here.

## Similar Packages

Other packages have implemented features in this domain.

- [{brochure}](https://github.com/ColinFay/brochure): This package
  appears to have a great deal of overlap with {scenes}. Colin Fay’s
  implementation appears to potentially be more robust and more complete
  than {scenes}, but at the cost of diverging farther from a “normal”
  shiny app.
- [{shiny.router}](https://appsilon.com/shiny-router-020/): This package
  from [Appsilon](https://appsilon.com) appears to be conceptually
  similar to {scenes}, but focused on routing based on URL. Of the three
  packages listed here, this is the only one available on CRAN.
- [{blaze}](https://github.com/nteetor/blaze): This package from Nate
  Teetor also focuses on routing based on URL. The resulting shiny apps
  are switched via the server function.

## Code of Conduct

Please note that the scenes project is released with a [Contributor Code
of
Conduct](https://contributor-covenant.org/version/2/1/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
