# DS112tutorials

This package was created for my COMP/STAT 112: *Introduction to Data Science* class at Macalester College so they could work through {learnr} tutorials. It is under development during this time and will be updated regularly. In order to stay up to date, you should reinstall the package regularly. I will update this message when the package is more stable.

To use this package:

1. Install the {devtools} package by running the following code in your console. You ONLY need to do this the first time or after you upgrade R. And, if you are using the server, do not install this as it's already on the server.

```{r}
install.packages(devtools)
```

2. Install the {DS112tutorials} package by running the following code in your console. If you are on the server, delete the `dependencies=TRUE` part.

```{r}
devtools::install_github("llendway/DS112tutorials", dependencies=TRUE)
```
3. Load the {learnr} library by running the following in your console:

```{r}
library(learnr)
```

4. To run one of the {learnr} tutorials, type something like the following into the console, where the first argument is the name of the tutorial:

```{r}
run_tutorial("ggplot_dplyr_intro", package="DS112tutorials")
```

