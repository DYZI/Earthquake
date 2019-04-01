[![Build Status](https://travis-ci.com/DYZI/FARS.svg?branch=master)](https://travis-ci.com/DYZI/Earthquake)
Travis

[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/DYZI/Earthquake?branch=master&svg=true)](https://ci.appveyor.com/project/DYZI/Earthquake)
 AppVeyor

## earthquakr R package

This is a small R package for cleaning, timelining, and mapping [NOAA Significant Earthquake data](https://www.ngdc.noaa.gov/nndc/struts/form?t=101650&s=1&d=1).

### About

This R package was originally built to satisfy the requirements of the Capstone project for the [Coursera](http://www.coursera.org) [Mastering Software Development in R](https://www.coursera.org/specializations/r) 5-course specialization.

### Installation

To install this package to run on your system, please first install and load the `devtools` package. Then you may install and load this package thus:

```r
devtools::install_github('c')
library(earthquake)
```
### Vignette

You may read the interactive vignette at my personal blog site, at: http://datawrangl.com/assets/earthquake-introduction.html.

Alternatively, read the introduction vignette using the command `vignette('introduction', package = 'earthquake')` after installation.  However, in order to do this, you must build the vignettes when installing, using the command `devtools::install_github('DYZI/Earthquake', build_vignettes = TRUE)`
