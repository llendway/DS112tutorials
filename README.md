# DS112tutorials

This package was created for my COMP/STAT 112: *Introduction to Data Science* class at Macalester College so they could work through {learnr} tutorials. It is under development during this time and will be updated regularly. In order to stay up to date, you should reinstall the package regularly. I will update this message when the package is more stable.

To use this package, install it by running the following code in your console:

```{r}
devtools::install_github("llendway/DS112tutorials")
```

Then, to run one of the {learnr} tutorials, type something like the following into the console, where the first argument is the name of the tutorial:

```{r}
library(learnr)
run_tutorial("ggplot_dplyr_intro", package="DS112tutorials")
```

