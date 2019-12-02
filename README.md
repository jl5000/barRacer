
<!-- README.md is generated from README.Rmd. Please edit that file -->
barRacer <img src='man/figures/logo.png' align="right" height="138" />
======================================================================

<!-- badges: start -->
<!-- badges: end -->
The goal of barRacer is to provide a simple function to generate bar chart race animations using `ggplot2` and `gganimate`.

Installation
------------

This package is not yet on CRAN.

You can install the development version of barRacer from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("jl5000/barRacer")
```

Example
-------

This simple example uses the `gapminder` dataset:

``` r
#install.packages("gapminder")
library(barRacer)

bar_chart_race(gapminder::gapminder, country, pop, year, title = "Population over time")
```

<img src="man/figures/README-example-1.gif" width="100%" />

Feedback
--------

If you have any issues or feedback, please do raise a Github Issue or create a Pull Request. All donations gratefully received.

<style>.bmc-button img{width: 35px !important;margin-bottom: 1px !important;box-shadow: none !important;border: none !important;vertical-align: middle !important;}.bmc-button{padding: 7px 5px 7px 10px !important;line-height: 35px !important;height:51px !important;min-width:217px !important;text-decoration: none !important;display:inline-flex !important;color:#ffffff !important;background-color:#FF813F !important;border-radius: 5px !important;border: 1px solid transparent !important;padding: 7px 5px 7px 10px !important;font-size: 20px !important;letter-spacing:-0.08px !important;box-shadow: 0px 1px 2px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 1px 2px 2px rgba(190, 190, 190, 0.5) !important;margin: 0 auto !important;font-family:'Lato', sans-serif !important;-webkit-box-sizing: border-box !important;box-sizing: border-box !important;-o-transition: 0.3s all linear !important;-webkit-transition: 0.3s all linear !important;-moz-transition: 0.3s all linear !important;-ms-transition: 0.3s all linear !important;transition: 0.3s all linear !important;}.bmc-button:hover, .bmc-button:active, .bmc-button:focus {-webkit-box-shadow: 0px 1px 2px 2px rgba(190, 190, 190, 0.5) !important;text-decoration: none !important;box-shadow: 0px 1px 2px 2px rgba(190, 190, 190, 0.5) !important;opacity: 0.85 !important;color:#ffffff !important;}</style>
<link href="https://fonts.googleapis.com/css?family=Lato&subset=latin,latin-ext" rel="stylesheet"><a class="bmc-button" target="_blank" href="https://www.buymeacoffee.com/ryBS4OP"><img src="https://cdn.buymeacoffee.com/buttons/bmc-new-btn-logo.svg" alt="Buy me a coffee"><span style="margin-left:15px;font-size:19px !important;">Buy me a coffee</span></a>
