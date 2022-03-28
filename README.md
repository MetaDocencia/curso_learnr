# curso_learnr
Materiales del curso de learnr

# Creating interactive tutorials with {learnr} package

## Pre workshop instructions

To participate in the workshop you can either work locally (if you have R and RStudio installed on your machine) or use an instance of R at RStudio Cloud.

* Using RStudio Cloud
If you want to use RStudio Cloud you will need a free account. Go to rstudio.cloud/ and follow de instructions to register. Keep in mind that the free account is limited to 15 hours per month and you don’t want to use it all before the workshop. We’ll provide a link to a pre-configured RStudio project during the workshop. You don’t have to do anything else.

* Working locally
Please check if you have R (>4.0) and Rstudio installed. You will also need to install a few packages:

``` r
install.packages("earnr")
install.packages("tidyverse")
install.packages("palmerpenguins")
devtools::install_github("rundel/learnrhash")
devtools::install_github("rstudio-education/gradethis")
```
And follow the instructions below to make sure you can work with R Markdown files. 

Go to File -> New File -> R Markdown. Click on “Ok” to create a new file. RStudio will ask your permission to install several packages. Go ahead and do it.

You can remove the file you just created.

We'll provide a link to download a project with all the files you'll need during the workshop.

(optional) If you are not familiar with Markdown, you can follow this short tutorial: https://commonmark.org/help/tutorial/


## Course materials

- [Presentation used during the course](https://docs.google.com/presentation/d/1RejcfLcXZtkZgOTOwo5UJx9Oyg-jU_vE5ucufnUx31Y/edit?usp=sharing)
- [RStudio Project used during this course](https://github.com/MetaDocencia/curso_learnr/blob/main/learnr_project.zip)


