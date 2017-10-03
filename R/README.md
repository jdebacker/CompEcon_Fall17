## R (and Python) for Econometrics
This module of the course covers non-structural econometric methods and how to apply these tools using open source software: mainly in R, but also in Python.

## Installing R and Setting up Kernal for Jupyter Notebooks

Do the following:
1. [Install R from CRAN](https://cran.r-project.org)
2. If you want an popular IDE for R, [intall RStudio](https://www.rstudio.com)
3. With R installed, go to your command line and do the following to create an R kernal for Jupyter Notebooks:
    * `$ R` # to launch R
    * `install.packages(c('repr', 'IRdisplay', 'evaluate', 'crayon', 'pbdZMQ', 'devtools', 'uuid', 'digest'))`
    * `devtools::install_github('IRkernel/IRkernel')`
    * `IRkernel::installspec()` or, to install system-wide for all users do `IRkernel::installspec(user = FALSE)`

Additionally, if you like Atom and want to continue using it for writing R scripts, you will want to add the following plug-ins:
* `linter-lintr` # linter for R
* `language-r` # syntax highlighting for R
* `r-exec` # to execute R from Atom

(Note Anaconda's package manager Conda does manage R packages, but at least in my experience with OSX, this manager is broken.  Thus I recommend installing from CRAN as outlined above.)

## Notebooks we worked through in class

*


## Useful Links

* [Guide to R for Stata Users](http://dss.princeton.edu/training/RStata.pdf)
* [Stata to Python cheat sheet](https://cheatsheets.quantecon.org/stats-cheatsheet.html)
* [QuantEcon: Linear regression in Python](https://lectures.quantecon.org/py/ols.html)
