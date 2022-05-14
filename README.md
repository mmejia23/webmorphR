
<!-- README.md is generated from README.Rmd. Please edit that file -->

# webmorphR

<img src="man/figures/logo.png" style="float:right;" />

<!-- badges: start -->

[![Codecov test
coverage](https://codecov.io/gh/debruine/webmorphR/branch/master/graph/badge.svg)](https://codecov.io/gh/debruine/webmorphR?branch=master)
<!-- badges: end -->

The goal of webmorphR is to make the construction of image stimuli more
reproducible, with a focus on face stimuli.

This development of this package was funded by ERC grant \#647910
(KINSHIP).

See <https://debruine.github.io/webmorphR/> for details on image
manipulations, making figures, and making stimuli.

## Installation

You can install the development version from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("debruine/webmorphR")
```

![Individual images with their composite, illustrating delineation
points and lines](man/figures/ind-avg-1.png)

## Helper packages

There are also two helper packages that contain large demo stimulus
files or functions that require python and dlib.

``` r
devtools::install_github("debruine/webmorphR.stim")
devtools::install_github("debruine/webmorphR.dlib")
```
