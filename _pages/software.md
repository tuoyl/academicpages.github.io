---
permalink: /software/
title: "Software"
gallery:
header:
---

Software development using statistical methods or data that observered by instruments has always been a passion of mine.
A good deal of my time is spent to develop software and scripts allow astronomers to better analyze and understand the data. The softwares I developed are related to pulsar timing analysis, GRB data analysis (for SVOM/GRM), pipeline and docker container for HXMTDAS.


# hxmt_pipeline

[![pipeline status](https://code.ihep.ac.cn/hxmthsdc/hxmt_pipeline/badges/master/pipeline.svg)](https://code.ihep.ac.cn/hxmthsdc/hxmt_pipeline/-/commits/master)
[![coverage report](https://code.ihep.ac.cn/hxmthsdc/hxmt_pipeline/badges/master/coverage.svg)](https://code.ihep.ac.cn/hxmthsdc/hxmt_pipeline/-/commits/master)

I am a developer of the [hxmt_pipeline](https://code.ihep.ac.cn/hxmthsdc/hxmt_pipeline) package for generating postestimation quantities of interest from Bayesian models. The package contains functions for producing regression tables, plotting predicted probabilities, calculating first differences, creating coefficient plots, and many other quantities. You can view the [Journal of Open Source Software](https://joss.theoj.org/) article for the package [here](https://doi.org/10.21105/joss.01722).

{% include gallery %}

To install the latest release on CRAN:

```r
install.packages("BayesPostEst")
```

The latest [development version](https://github.com/ShanaScogin/BayesPostEst) on GitHub can be installed with:

```r
library(remotes)
install_github("ShanaScogin/BayesPostEst")
```

You can try out the `mcmcCoefPlot` function from the package in the interactive R console below:

# RWmisc

[![R build status](https://github.com/jayrobwilliams/RWmisc/workflows/R-CMD-check/badge.svg)](https://github.com/jayrobwilliams/RWmisc/actions)
[![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/RWmisc)](https://CRAN.R-project.org/package=RWmisc)
[![codecov](https://codecov.io/gh/jayrobwilliams/RWmisc/branch/master/graph/badge.svg)](https://codecov.io/gh/jayrobwilliams/RWmisc)

I've collected convenience functions that I've written to address issues I frequently confront in my work into a personal R package called [RWmisc](https://CRAN.R-project.org/package=RWmisc). It includes functions for:

- Managing multiple different projections for cross-national spatial data
- Converting latitude-longitude data in archaic forms (degrees, minutes, seconds)
- Correcting for overlapping polygons when aggregating raster data to polygons
- My custom minimal ggplot2 theme

![](/images/software/spatial_weighting.png)

To install the latest release on CRAN:

```r
install.packages("RWmisc")
```

The latest [development version](https://github.com/jayrobwilliams/RWmisc) on GitHub can be installed with:

```r
library(remotes)
install_github("jayrobwilliams/RWmisc")
```

# Other resources

I also have a number of other software resources focused on making computation and academic life easier:

- [The template](https://github.com/jayrobwilliams/JobMarket) I use for my academic job market materials
    - Fill in school/position information in one file and it populates to all statements
    - Generate summary statistics from teaching evaluations and integrate into statements
    - Combine multiple teaching evaluations into a single portfolio document
    - Do all of this programmatically with GNU Make!
- [The template](https://github.com/jayrobwilliams/UNC-Dissertation-Template) I used for my dissertation
    - This satisfied the formatting requirements at UNC in 2019
    - Some tweaking likely required to use at another institution or in the future
- [Scripts](https://github.com/jayrobwilliams/Teaching) that I use to save time on various teaching-related tasks like grading
- [Functions](https://github.com/jayrobwilliams/ComputerVision) for extracting still frames from videos and information from images in Python using OpenCV
- [Compiling OpenCV](/files/html/OpenCV_Install.html) from source for Anaconda virtual environments instead of Homebrew ones or system Python installations
