
<!-- README.md is generated from README.Rmd. Please edit that file -->
Introduction to data visualisation using R: Osama Mahmoud
---------------------------------------------------------

[![Build Status](https://travis-ci.org/statcourses/BristolVis.svg?branch=master)](https://travis-ci.org/statcourses/BristolVis)

This page provides practicals and materials of the [data visualisation course](http://www.bristol.ac.uk/medical-school/study/short-courses/Introduction-to-Data-Visualisation-and-Web-Applications-Using-R/) held at the University of Bristol, January 2019.

-   PDF version of course slides: [The course slides](https://raw.githubusercontent.com/statcourses/BristolVis/master/slides.pdf) on advanced graphics using [ggplot2](https://cran.r-project.org/web/packages/ggplot2/) is made available here.

-   R reference card for `Introduction to R`: The [R reference card](https://raw.githubusercontent.com/statcourses/BristolVis/master/Refcard_IntroR.pdf) summarises some useful basic commands, concepts and functions.

-   R studio cheat sheet for `ggplot2`: The R studio [cheat sheet](https://raw.githubusercontent.com/statcourses/BristolVis/master/ggplot2-cheatsheet.pdf) for the ggplot2 functions is included.

Installing the `BristolVis` package
-----------------------------------

The course uses a variety of data examples, R packages and practical sheets. The easiest way of downloading and installing all dependencies is first to install the R package associated with this course, named 'BristolVis'. It can be simply installed by running the following code lines into your R session.

``` r
install.packages("drat")
drat::addRepo("statcourses")
install.packages("BristolVis")
```

Usage of practicals
-------------------

The `BristolVis` package includes a number of practical files to guide learners to advanced graphics using R.

These practicals can be displayed by:

``` r
vignette("prac_base", package = "BristolVis")
```

The course web-tool
-------------------

I have designed a web-tool, named `RVis`, to help me delivering this course. It enables exploring the training data sets, generating graphics, presenting summary results in an interactive way. You can [check it out from here](http://bristol-medical-stat.bristol.ac.uk:3838/RVis/).

Other courses and their associated packages
-------------------------------------------

You can view the entire set of my courses from [my personal website](http://osmahmoud.com/R-courses/) or the [stat-courses website](https://statcourses.github.io/).
