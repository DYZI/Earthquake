[![Build Status](https://travis-ci.org/DYZI/Earthquake.svg?branch=master)](https://travis-ci.org/DYZI/Earthquake)
Travis

[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/DYZI/Earthquake?branch=master&svg=true)](https://ci.appveyor.com/project/DYZI/Earthquake)
 AppVeyor

## earthquake package in R

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

You may read the interactive vignette at my personal blog site, at: https://github.com/DYZI/Earthquake/blob/master/vignettes/introduction.Rmd

Alternatively, read the introduction vignette using the command `vignette('introduction', package = 'earthquake')` after installation.  However, in order to do this, you must build the vignettes when installing, using the command `devtools::install_github('DYZI/Earthquake', build_vignettes = TRUE)`


### Review Criteria
•	Your package must be hosted on [GitHub repository](https://github.com/DYZI/Earthquake). 
You will be providing the URL to your package on GitHub so that other students can evaluate your work.

•	Your package must at least contain the following directories: 
 [R](https://github.com/DYZI/Earthquake/tree/master/R)?,
 [man](https://github.com/DYZI/Earthquake/tree/master/man)?,
 [tests](https://github.com/DYZI/Earthquake/tree/master/tests)?,
 [vignettes](https://github.com/DYZI/Earthquake/tree/master/vignettes)?.
 
•	Your package must at least contain the following files: 
[.travis.yml](https://github.com/DYZI/Earthquake/tree/master/.travis.yml), 
[DESCRIPTION](https://github.com/DYZI/Earthquake/tree/master/DESCRIPTION), 
[LICENSE](https://github.com/DYZI/Earthquake/tree/master/LICENSE) , 
[NAMESPACE](https://github.com/DYZI/Earthquake/tree/master/NAMESPACE), 
[README.md](https://github.com/DYZI/Earthquake/tree/master/README.md).

•	Every function in your package must have a corresponding [test](https://github.com/DYZI/Earthquake/tree/master/tests)?,

•	Every function in your package must have at least one example in its [documentation](https://github.com/DYZI/Earthquake/tree/master/man).

•	Your package must have a [vignette](https://github.com/DYZI/Earthquake/tree/master/vignettes) which provides an explanation of the purpose for your package and how it could be used. The vignette should include examples for every function that is exported in the package's NAMESPACE file.

•	A [Travis badge] that says "[![Build Status](https://travis-ci.org/DYZI/Earthquake.svg?branch=master)](https://travis-ci.org/DYZI/Earthquake)" that is linked to your package's. Travis build should appear at the top of your README.md file on GitHub.

•	Your package must be [tested using Travis](https://travis-ci.org/DYZI/Earthquake). There should be no errors, warnings, or notes at the end of your Travis build, and all of your tests should be run on Travis.

