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
- Makes compiled code easier to use

A Few Package Myths
=======================================================

Packages: 
- do not have to be listed on CRAN (and getting them on CRAN can be 
more hassle than its worth)
- do not have to be constantly updated (though major changes in their 
dependencies can make them hard to use)
- do not have to be distributed (you can use them locally)
- do not have to invent new statistical methods (convenience functions are great)
- do not have to be big (a simple thing done well...)

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

Makes an `R/` directory, `DESCRIPTION` file, and `NAMESPACE` file + an RStudio 
project

Demo
=====================================================

Code all the things

<iframe src="http://giphy.com/embed/g8GfH3i5F0hby?html5=true" width="480" height="339" frameBorder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>


Common Issues
================================================

- Generics, methods, classes
- Documentation
- Dependencies and imports
- Unit testing and reversion

Planning
=================================================

Think about the organization of your package a lot. Just like writing, you may 
find yourself reorganizing a few times as the package changes. 


