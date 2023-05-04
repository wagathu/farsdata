
<!-- README.md is generated from README.Rmd. Please edit that file -->

# farsdata

<!-- badges: start -->

[![Travis build
status](https://travis-ci.com/njuguna-brian/farsdata.svg?branch=main)](https://travis-ci.com/njuguna-brian/farsdata)
[![R-CMD-check](https://github.com/njuguna-brian/farsdata/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/njuguna-brian/farsdata/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of farsdata is to provide a set of functions that can be used to read, summarize, and plot the Fatality Analysis Reporting System(FARS) data.

## Installation

You can install the development version of farsdata from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("njuguna-brian/farsdata")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(farsdata)
make_filename(2013)
```
