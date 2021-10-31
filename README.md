
<!-- README.md is generated from README.Rmd. Please edit that file -->

# styler.unify

The goal of {styler.unify} is providing code cleaning but keep `<-` as
`=`. It is a third-party style guide for
[{styler}](https://styler.r-lib.org).

## Installation

You can install the released version of {styler.unify} from
[GitHub](https://github.com) with:

``` r
remotes::install_github("BioSisyphus/styler.unify")
```

## Example

This is a basic example of how to style code with it.

``` r
library(styler.unify)
cache_deactivate()
text <- "x <- 4
y = 3
a;
"

style_text(text)
```
