Packaging with R
========================================================
author: Jared Knowles
date: 04/17/2015

What is a Package?
========================================================

- A package is a bundle of code, data, and documentation in a standardized 
format that is easy to share
- Some common examples are: `plyr`, `knitr`, `caret`, `MASS`
- Packages have varying degrees of complexity depending on their intended use
- Packages are like mobile apps, except they don't have ads, they don't make you 
buy *stars* to keep playing, and they don't have terrible ads on TV




What's in a Package?
=======================================================

Required: 

- `R/` directory
- `DESCRIPTION` file
- `NAMESPACE` file
- `man` directory for documentation

Recommended: 

- `tests`
- `data`
- `LICENSE` for the code
- `README`

Why Package?
========================================================

- It's standardized
- It's shareable
- It's maintainable
- You can contribute to your favorite packages easier


A Warning
=======================================================

Packages have many layers and today I'll only cover the basics

<iframe src="http://giphy.com/embed/nNrjb4sNrZzMI?html5=true" width="480" height="270" frameBorder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>



Beware: Not Always Clear
====================================================

<iframe src="http://giphy.com/embed/52HjuHsfVO69q?html5=true" width="480" height="270" frameBorder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>


Getting Started
====================================================

To make R packages, you'll need a few tools:

- R-devel (or on Windows, [Rtools](http://cran.r-project.org/bin/windows/Rtools/))
- [RStudio](http://www.rstudio.com)
- Packages: `devtools`, `roxygen2`, `testthat`
- Version control system

Overview
========================================================

- A little about the basics of package development
- Live coding demo of creating a package from scratch
- Return to discussion of common issues with package development
- Q&A

Basics
=======================================================

The RStudio/devtools toolchain makes it easier to get started with package 
development than ever. 

`devtools::create("path/to/package/pkgname")`

Makes - an `R/` directory, `DESCRIPTION` file, and `NAMESPACE` file + an RStudio 
project




