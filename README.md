---
editor_options: 
  markdown: 
    wrap: 72
---

# D-Lab R SQL Fundamentals Workshop

[![DataHub](https://img.shields.io/badge/launch-datahub-blue)](DATAHUB_LINK_HERE)
[![Binder](https://mybinder.org/badge_logo.svg)](BINDER_LINK_HERE)
[![License: CC BY
4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains the materials for D-Lab R SQL Fundamentals
workshop.

### Prerequisites

Prior experience with [R
Fundamentals](https://github.com/dlab-berkeley/R-Fundamentals), [R Data
Wrangling](https://github.com/dlab-berkeley/R-Data-Wrangling), and [R
Data
Visualization](https://github.com/dlab-berkeley/R-Data-Visualization) is
assumed.

Check D-Lab's [Learning
Pathways](https://dlab-berkeley.github.io/dlab-workshops/python_path.html)
to figure out which of our workshops to take!

## Workshop Goals

In this workshop, we provide an introduction to using SQL to query and
retrieve data from relational databases in R. First, we’ll cover what
relational databases and SQL are. Then, we’ll use different packages in
R to navigate relational databases using SQL.

If you are not familiar with material in [R
Fundamentals](https://github.com/dlab-berkeley/R-Fundamentals), [R Data
Wrangling](https://github.com/dlab-berkeley/R-Data-Wrangling), and [R
Data
Visualization](https://github.com/dlab-berkeley/R-Data-Visualization),
we recommend attending those workshops first.

## Learning Objectives

After this workshop, you will be able to:

1.  Explain what a relational database is and why we would want to use
    it.

2.  Access and query a database using SQL.

3.  Use `DBI` and `dbplyr` to query data from a relational database.

This workshop does not cover the following:

-   Read and conduct basic data operations in R. These are covered in [R
    Fundamentals](#0).
-   Wrangle data for basic data analysis using R. These are covered in
    [R Data Wrangling](#0).

## Installation Instructions

We will use RStudio to go through the workshop materials, which requires
installation of both the R language and the RStudio software. Complete
the following steps:

1.  [Download R](https://cloud.r-project.org/): Follow the links
    according to the operating system that you are running. Download the
    package, and install R onto your compute. You should install the
    most recent version (at least version 4.0).
2.  [Download
    RStudio](https://rstudio.com/products/rstudio/download/#download):
    Install RStudio Desktop. This should be free. Do this after you have
    already installed R. The D-Lab strongly recommends an RStudio
    edition of 2022.02.0+443 "Prairie Trillium" or higher.
3.  [Download these workshop
    materials](https://github.com/dlab-berkeley/R-Data-Visualization):
    1.  Click the green "Code" button in the top right of the repository
        information.
    2.  Click "Download Zip".
    3.  Extract this file to a folder on your computer where you can
        easily access it (we recommend Desktop).
4.  Optional: if you’re familiar with git, you can instead clone this
    repository by opening a terminal and entering [GitCloneCommand].

## Is R not working on your laptop?

If you do not have R installed and the materials loaded on your workshop
by the time it starts, we *strongly* recommend using the UC Berkeley
Datahub to run the materials for these lessons. You can access the
DataHub by clicking [this
link](https://datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FR-Data-Visualization&urlpath=rstudio%2F&branch=main).

The DataHub downloads this repository, along with any necessary
packages, and allows you to run the materials in an RStudio instance on
UC Berkeley's servers. No installation is necessary from your end - you
only need an internet browser and a CalNet ID to log in. By using the
DataHub, you can save your work and come back to it at any time. When
you want to return to your saved work, just go straight to
[DataHub](https://datahub.berkeley.edu), sign in, and you click on the
`R-SQL-Fundamentals` folder.

## Run the Code

Now that you have all the required software and materials, you need to
run the code:

Provide instructions on running the code, including how to load relevant
software (RStudio, Jupyter Notebooks, etc.) and which file to open up.
See other repositories for examples.

Additionally, provide instructions on how to run code once it’s open
(running Jupyter cells, RMarkdown cells, etc.).

# Additional Resources

Check out the following resources to learn more about using SQL in R:

-   Errickson, J. 2024. STATS 506. [Computational Methods and Tools in
    Statistics](https://dept.stat.lsa.umich.edu/~jerrick/courses/stat506_f24/07-sql.html)

-   [Data Analysis and Visualization in R for
    Ecologists](https://datacarpentry.github.io/R-ecology-lesson/instructor/05-r-and-databases.html)

# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to
advance data-intensive social science and humanities research. Our goal
at D-Lab is to provide practical training, staff support, resources, and
space to enable you to use R for your own research applications. Our
services cater to all skill levels and no programming, statistical, or
computer science backgrounds are necessary. We offer these services in
the form of workshops, one-to-one consulting, and working groups that
cover a variety of research topics, digital tools, and programming
languages.

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more
about us. You can view our
[calendar](https://dlab.berkeley.edu/events/calendar) for upcoming
events, learn about how to utilize our
[consulting](https://dlab.berkeley.edu/consulting) and
[data](https://dlab.berkeley.edu/data) services, and check out upcoming
[workshops](https://dlab.berkeley.edu/events/workshops).

# Here are other R workshops offered by the D-Lab:

## Basic Competency

-   [Fast-R](https://github.com/dlab-berkeley/Fast-R)
-   [R Data Wrangling](https://github.com/dlab-berkeley/R-wrang)
-   [R Functional
    Programming](https://github.com/dlab-berkeley/R-functional-programming)
-   [Geospatial Fundamentals in R with
    sf](https://github.com/dlab-berkeley/Geospatial-Fundamentals-in-R-with-sf)
-   [Census Data in
    R](https://github.com/dlab-berkeley/Census-Data-in-R)

## Intermediate/Advanced Competency

-   [Advanced Data Wrangling in
    R](https://github.com/dlab-berkeley/advanced-data-wrangling-in-R)
-   [Unsupervised Learning in
    R](https://github.com/dlab-berkeley/Unsupervised-Learning-in-R)
-   [R Machine Learning with
    tidymodels](https://github.com/dlab-berkeley/Machine-Learning-with-tidymodels)
-   [Introduction to Deep Learning in
    R](https://github.com/dlab-berkeley/Deep-Learning-in-R)
-   [R Package
    Development](https://github.com/dlab-berkeley/R-package-development)

# Contributors

-   [Taesoo Song](https://taesoosong.github.io/)
