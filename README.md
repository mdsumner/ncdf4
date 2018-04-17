
[![Travis build status](https://travis-ci.org/mdsumner/ncdf4.svg?branch=master)](https://travis-ci.org/mdsumner/ncdf4) [![AppVeyor build status](https://ci.appveyor.com/api/projects/status/github/mdsumner/ncdf4?branch=master&svg=true)](https://ci.appveyor.com/project/mdsumner/ncdf4)

<!-- README.md is generated from README.Rmd. Please edit that file -->
ncdf4
=====

The goal of ncdf4 is to provide an "Interface to Unidata netCDF (Version 4 or Earlier) Format Data Files".

This fork of the CRAN package `ncdf4` is intended to update the Windows build process, and specifically to add support for Thredds.

Todo
----

-   check Makevars.win (assume can remove "DHAVE\_LIBUDUNITS2" but what about "-DHAVE\_DECL\_NC\_RENAME\_GRP=1"?)
-   add tests, especially for Thredds (make sure 32-bit Windows limitation is understood)
-   roxygenize?

Installation
------------

You can install the released version of ncdf4 from [CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("ncdf4")
```

And the development version from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("mdsumner/ncdf4")
```

Example
-------
