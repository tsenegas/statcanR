
<!-- README.md is generated from README.Rmd. Please edit that file -->

# statcanR

<!-- badges: start -->

[![Travis build
status](https://travis-ci.org/warint/statcanR.svg?branch=master)](https://travis-ci.org/warint/statcanR)
<!-- badges: end -->

The goal of statcanR is to get all to get all Canadian statistics data
(CANSIM tables,now identify by Product IDs (PID)) without any limitation
and provided by the new Statistics Canada Web Data Service.

## Installation

You can install the released version of statcanR from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("statcanR")
```

## Example

This is a basic example which shows you how to get Canadian data

``` r
library(statcanR)
data <- getCansimTbl("14-10-0063-01", "eng")
```
