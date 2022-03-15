
<!-- README.md is generated from README.Rmd. Please edit that file -->

# camtraptor

<!-- badges: start -->

[![R-CMD-check](https://github.com/inbo/camtraptor/workflows/R-CMD-check/badge.svg)](https://github.com/inbo/camtraptor/actions)
[![codecov](https://codecov.io/gh/inbo/camtraptor/branch/main/graph/badge.svg)](https://app.codecov.io/gh/inbo/camtraptor/)
[![repo
status](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![funding](https://img.shields.io/static/v1?label=funded+by&message=FWO+for+lifewatch.be&labelColor=1a4e8a&color=f15922)](https://lifewatch.be/)
![last
commit](https://img.shields.io/github/last-commit/inbo/camtraptor)
<!-- badges: end -->

Camtraptor is an R package to read, explore and visualize Camera Trap
Data Packages ([Camtrap DP](https://tdwg.github.io/camtrap-dp/)).
Camtrap DP is a community developed data exchange format for this type
of data. With camtraptor you can read and filter data and create maps
and overviews observed species, relative abundance index, and show these
per deployment on a map.

To get started, see:

-   [Vignettes](https://inbo.github.io/camtraptor/articles/): tutorials
    showcasing functionality.
-   [Function
    reference](https://inbo.github.io/camtraptor/reference/index.html):
    overview of all functions.

## Installation

You can install the development version of camtraptor from
[GitHub](https://github.com/inbo/camtraptor) with:

``` r
# install.packages("devtools")
devtools::install_github("inbo/camtraptor")
```


library(camtraptor)
```

## camtraptor vs camtrapR and activity

Camtraptor wants to provide and bundle much needed functionality to
read, explore and visualize Camera Trap Data Packages. Over time we hope
to include some or all of this functionality in widely used R packages
such as [camtrapR](https://cran.r-project.org/package=camtrapR) and
[activity](https://cran.r-project.org/package=activity).

## Meta

-   We welcome [contributions](.github/CONTRIBUTING.md) including bug
    reports.
-   License: MIT
-   Get citation information for `camtraptor` in R doing
    `citation("camtraptor")`.
-   Please note that this project is released with a [Contributor Code
    of Conduct](.github/CODE_OF_CONDUCT.md). By participating in this
    project you agree to abide by its terms.
