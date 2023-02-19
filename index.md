--- 
title: "Random Learning"
author: "Drake Asberry"
date: "19 FEB 2023"
site: bookdown::bookdown_site
documentclass: book
bibliography: [book.bib, packages.bib]
biblio-style: apalike
link-citations: yes
description: "This is a working example of my own learning resources that I have compiled over my years of as a learner, tinker and problem solver. The output format for this example is bookdown::gitbook."
---

# Introduction

This website was created out of a need to document my own learning process as I tackled programming challenges and problem sets. This site is to be used for educational purposes only and the author assumes no responsibility for how an end-user chooses to utilize information. The author also assumes no risk or responsibility for any damages or adverse affects to any hardware or software systems the end-user encounters as a result of using/running any code found on this website. Code is not a required maintenance obligation for the author and cannot verify whether any code contained within will operate or be run in a stable reliable environment.


```{r eval=FALSE, include=FALSE}
# The **bookdown** package can be installed from CRAN or Github:
install.packages("bookdown")
# or the development version
# devtools::install_github("rstudio/bookdown")
```


```{r include=FALSE}
# automatically create a bib database for R packages
knitr::write_bib(c(
  .packages(), 'bookdown', 'knitr', 'rmarkdown'
), 'packages.bib')
```
