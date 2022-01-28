
# Introduction to R workshop


<!-- badges: start -->
<!-- badges: end -->

## Goals

The goal of the workshop is to introduce git, RStudio, and some basics of R. If we have time we will also cover
data wrangling with `dplyr`, and data visualization with `ggplot2`. All of this is done
through the use of baseball data from package `Lahman`.

## Class recording
https://duke.zoom.us/rec/share/Vy3r4xb9dMdVSqZmcIuzTmz4Bg3473Sj_HIXPd2wGEj10RW_yl4mpgqMiBHQOImO.LIlQtOpboHMV96RP?startTime=1643332043000 
## Getting started

Downloading R, git, and RStudio

R: 
Choose link under 0-cloud, then choose appropriate install based on computer. 
https://cran.r-project.org/mirrors.html 

Github: 
Create an account if you do not have one.
https://github.com/ 

Git: 
Download git using instructions here
https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/setting-up-git

RStudio: 
Download RStudio Desktop
https://www.rstudio.com/products/rstudio/download/


### If you want to work in the Docker containers

To bring these files into an RStudio session follow the steps below.

1. Click on the green Code button in this repository, and copy the git URL
   (it should end in .git).

2. Go to your RStudio Docker container at
   https://vm-manage.oit.duke.edu/containers/rstudio.

3. In RStudio, go to File → New Project → Version Control → Git.

4. Paste the git URL you copied in (1) into the dialog box labeled Repository
   URL. Adjust the folder to where you want this repository located.

5. Click Create Project, and the files from your GitHub repo will be displayed
   in the Files pane in RStudio.

6. Click class.Rmd to open the R Markdown file.

## Packages

>In R, the fundamental unit of shareable code is the package. A package bundles
together code, data, documentation, and tests, and is easy to share with others.
<br/><br/>
-Hadley Wickham and Jenny Bryan

This analysis makes use of two packages: `tidyverse` and `Lahman`. The
`tidyverse` is a collection of packages. The analysis will use the `dplyr` and
`gpplot2` packages that are automatically loaded when `tidyverse` is loaded.

If you find you are missing a package, install it with the below code.

```r
install.packages("package_name")
```

Be sure to spell the package correctly and put it in quotes.

## Resources
Want to further your understanding of some of the functions used in the
analysis? Check out the resources folder of the repository. 

Want to learn on your own? See this document for a recommended learning pathway. 
https://docs.google.com/document/d/1fWET_GreI5qO2E-DDDojsmlfNeoQgZaCji-4D5M3PmA/edit#


The below books are also great resources. R Cookbook is for beginners, while
R for Data Science does require some basic knowledge of R.

- R Cookbook - https://rc2e.com
- R for Data Science - https://r4ds.had.co.nz/
