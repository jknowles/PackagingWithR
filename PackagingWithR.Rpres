Packaging with R
========================================================
author: Jared Knowles
date: 04/17/2015

Why me?
======================================================

I have one very small package on CRAN and am co-author of another. 

I have submitted patches accepted to a few other packages. 

I think I can make this fun...

Fun
=====================================================

<iframe src="http://giphy.com/embed/Tk1RH495RjYYM?html5=true" width="480" height="268" frameBorder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>

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

- `tests` directory of unit tests
- `data` directory of example data
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
- You do not have to be Hadley to publish a package

A Warning
=======================================================

Packages have many layers and today I'll only cover the basics

<iframe src="http://giphy.com/embed/nNrjb4sNrZzMI?html5=true" width="480" height="270" frameBorder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>

Planning
=================================================

Think about the organization of your package a lot. Just like writing, you may 
find yourself reorganizing a few times as the package changes. 

Function naming is hard and you are going to have to revisit it. 


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

Let's live-code up a whole package...

<iframe src="http://giphy.com/embed/h9KtiB6DgiS2s?html5=true" width="480" height="300" frameBorder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>


Beware: Not Always Clear
====================================================

<iframe src="http://giphy.com/embed/52HjuHsfVO69q?html5=true" width="480" height="270" frameBorder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>


Common Issues
================================================

- Generics, methods, classes
- Documentation
- Weird edge cases
- Dependencies and imports
- Unit testing and reversion

Generics, methods, and classes
=================================================

- Generics are functions like `print` and `summary`
- Methods are kind of like generics, but apply to S4 classes
- Classes are object types like `list`, `lm`, etc. that help define how 
an object behaves
- This can get seriously confusing

<iframe src="http://giphy.com/embed/nc6uU493LXH1u?html5=true" width="480" height="360" frameBorder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>

Documentation
================================================

Remember how much you hate documentation of some R functions like `?list` or 
`?lapply` or `?merge` or `?by` -- well now it's on you

Some ideas -- *use Roxygen*, write examples, and link examples and unit tests 
to save yourself time

It's required to publish on CRAN and it's important to your users. Plus, it's 
hard to catch up on... 

Why did I do this?
=========================================

<iframe src="http://giphy.com/embed/4ytUZzb1pRPBS?html5=true" width="480" height="302" frameBorder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>

Edge Cases
=====================================

Your package has two users at least -- you now, and future you. You would 
be amazed at the *dumb* things future you might try to do:

<iframe src="http://giphy.com/embed/YePP5jKb0xmxi?html5=true" width="480" height="350" frameBorder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>

Edge cases include
=======================================
 
- `NULL` objects
- Objects with some items missing
- Really big or really small objects
- When an object fails
- Mistyped or incorrectly specified parameters
- Nonstandard evaluation

Dependencies and imports
===============================================

The more you rely on others...

<iframe src="http://giphy.com/embed/Yn33HO11fNRUk?html5=true" width="480" height="270" frameBorder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>

Dependencies are a double edged sword
================================================

- Easier to use someone else's code, but now you're at their mercy
- Hard to make sure R's `NAMESPACE` stays clean the more things you depend on 
- If the upstream package changes, your code might break
- Can get confusing, fast

Unit testing
============================================

As you and future you collaborate more, you are going to make changes

<iframe src="http://giphy.com/embed/10doVhFq3aV99S?html5=true" width="480" height="269" frameBorder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe>

Those changes won't always work


Unit tests
==============================================

Test whether your code does what you want in a specific case. As you make changes 
you just make sure your code continues to do the expected things. 

Sounds simple, but unit testing is hard, and most R packages have very few unit 
tests. 

But, a good unit test can speed development in the future.

Thanks and Contact Info
==========================

Jared Knowles

[www.jaredknowles.com](www.jaredknowles.com)

[www.github.com/jknowles](www.github.com/jknowles)

[@jknowles](www.twitter.com/jknowles)

jknowles AT gmail DOT com



