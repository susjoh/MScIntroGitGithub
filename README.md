# MSc Course: Introduction to git and GitHub
## Creating reproducible workflows in RStudio.

This repository contains a tutorial on reproducible research for the Professional Skills in Ecology and Evolution module in the MSc Ecology, Evolution and Biodiversity at the University of Edinburgh.

This practical covers: 

* Organising data and workflows with *RStudio*
* Reproducible analyses in *R*
* Version control with *git*
* Making projects available on *GitHub*.

To run the practical, run the following code in your RStudio console:

```
library(remotes)
install_github("susjoh/MScIntroGitGithub")
library("MScIntroGitGithub")
learnr::run_tutorial("MSc_Intro_to_Git_and_GitHub", package = "MScIntroGitGithub")

```

