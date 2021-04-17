
# Introduction to R workshop

Thursday, April 15, 2021

<!-- badges: start -->
<!-- badges: end -->

The goal of the workshop is to introduce some basics of R, data wrangling
with `dplyr`, and data visualization with `ggplot2`. All of this is done
through the use of baseball data from package `Lahman`.

## Getting started

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

6. Click baseball_analysis.Rmd to open the R Markdown file.

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

Want to further your understanding of some of the functions used in the
analysis? Check out the below resources on `dplyr` and `ggplot2`.

#### `dplyr` resources

- [Website](https://dplyr.tidyverse.org)
- [Cheatsheet](https://github.com/rstudio/cheatsheets/raw/master/data-transformation.pdf)

#### `ggplot2` resources

- [Website](https://ggplot2.tidyverse.org)
- [Cheatsheet](https://github.com/rstudio/cheatsheets/raw/master/data-visualization-2.1.pdf)

## Learn more R?

If you are interested in learning more about R in general, check out
[swirl](https://swirlstats.com). swirl teaches you R programming and data
science interactively, at your own pace, and right in the R console! You
can do this directly in the Duke OIT RStudio Docker Containers.

The below books are also great resources. R Cookbook is for beginners, while
R for Data Science does require some basic knowledge of R.

- R Cookbook - https://rc2e.com
- R for Data Science - https://r4ds.had.co.nz/
