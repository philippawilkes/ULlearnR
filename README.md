# ULlearnR

The goal of ULlearnR is to publish interactive tutorials for the UL module **"Data Analytics with R"**.

## Installation

You can install ULlearnR from [GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("philippawilkes/ULlearnR")
```
## Interactive tutorials

### Launching from the Tutorials pane

Once you have installed the package, you should be able to launch the tutorials from the "Tutorial" pane on the right-hand side of the RStudio IDE (provided that you have a recent version of RStudio installed). 


Press "Start Tutorial" and once it has loaded in the pane, press the button to open the tutorial in an internet browser.

Otherwise, you can launch them using the `run_tutorial()` function from the `learnr` package:

### Launching using `run_tutorial()`

#### Tutorial 4 - Data Preparation: Working with dates and tidy data

``` r
learnr::run_tutorial(name = "section_4_data_preparation",
                     package = "ULlearnR")
```

#### For Tutorials 1 to 3

``` r
devtools::install_github("edwardgunning/IDAlearnR")
```


