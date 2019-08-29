
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Tools for modeling bumblebee colony growth

<!-- badges: start -->

[![Travis build
status](https://travis-ci.org/Aariq/bumbl.svg?branch=master)](https://travis-ci.org/Aariq/bumbl)
[![AppVeyor build
status](https://ci.appveyor.com/api/projects/status/github/Aariq/bumbl?branch=master&svg=true)](https://ci.appveyor.com/project/Aariq/bumbl)
[![Codecov test
coverage](https://codecov.io/gh/Aariq/bumbl/branch/master/graph/badge.svg)](https://codecov.io/gh/Aariq/bumbl?branch=master)
<!-- badges: end -->

`bumbl` implements a model for bumblebee colony growth described in
Crone and Williams 2019<sup>1</sup>. The `brkpt` function models colony
growth as having a change point at some time, *tau*, where the colony
switches from growth and worker production to gyne production. The
`bumbl` function applies this model to a dataframe of data from multiple
colonies, allowing for each colony to have it’s own *tau* and returns
the original data augmented with coefficients from the changepoint
model.

This is still in very early development, so use at your own risk.

More bumblebee related functions to come…

## Installation

You can install this development version of `bumbl` with:

``` r
devtools::install_github("Aariq/bumbl")
```

# References

<sup>1</sup>Crone, E. E., and Williams, N. M. (2016). Bumble bee colony
dynamics: quantifying the importance of land use and floral resources
for colony growth and queen production. Ecol. Lett. 19, 460–468.
<https://doi.org/10.1111/ele.12581>
