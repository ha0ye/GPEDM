
<!-- README.md is generated from README.Rmd. Please edit that file -->

# GPEDM

<!-- badges: start -->

[![Build
Status](https://travis-ci.org/ha0ye/GPEDM.svg?branch=master)](https://travis-ci.org/ha0ye/GPEDM)
[![codecov](https://codecov.io/gh/ha0ye/GPEDM/branch/master/graph/badge.svg)](https://codecov.io/gh/ha0ye/GPEDM)
<!-- badges: end -->

## Overview

The goal of GPEDM is to an accessible package for applying Gaussian
Process regression for Empirical Dynamic Modeling. The models are mainly
intended to modeling time series, and using Gaussian Processes to
perform the tricky step of inferring a reasonable model of the
underlying dynamics given the observed data.

## Installation

You can install GPEDM from GitHub with:

``` r
# install.packages("remotes")
remotes::install_github("ha0ye/GPEDM")
```

If you are on Windows, you may need to install
[Rtools](https://cran.r-project.org/bin/windows/Rtools/) first, so that
you have access to a C++ compiler.

## Example

``` r
library(GPEDM)
```
