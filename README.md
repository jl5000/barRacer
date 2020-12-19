
<!-- README.md is generated from README.Rmd. Please edit that file -->

# barRacer <img src='man/figures/logo.png' align="right" height="138" />

<!-- badges: start -->

[![Travis build
status](https://travis-ci.org/jl5000/barRacer.svg?branch=master)](https://travis-ci.org/jl5000/barRacer)
[![AppVeyor build
status](https://ci.appveyor.com/api/projects/status/github/jl5000/barRacer?branch=master&svg=true)](https://ci.appveyor.com/project/jl5000/barRacer)
<!-- badges: end -->

The goal of barRacer is to provide a simple function to generate bar
chart race animations using `ggplot2` and `gganimate`.

## Installation

This package is not yet on CRAN.

You can install the development version of barRacer from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("jl5000/barRacer")
```

## Example

This simple example uses the `gapminder` dataset:

``` r
#install.packages("gapminder")
library(barRacer)

bar_chart_race(gapminder::gapminder, country, pop, year, title = "Population over time")
```

<img src="man/figures/README-example-1.gif" width="100%" />

## Acknowledgements

  - Hadley Wickham for the [`tidyverse`](https://www.tidyverse.org/)
    (including `ggplot2`);
  - Thomas Lin Pedersen for
    [`gganimate`](https://gganimate.com/index.html);
  - Ray Larabie ([Typodermic Fonts](http://typodermicfonts.com)) for the
    *Hemi Head* font used in the hex logo.

## Feedback

If you have any issues or feedback, please do raise a Github Issue or
create a Pull Request.
