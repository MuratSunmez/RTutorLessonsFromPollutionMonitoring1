This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

This repository contains an interactive RTutor problem set based on:

> Axbard, S., & Deng, Z. (2024). *Informed enforcement: Lessons from pollution monitoring in China*. American Economic Journal: Applied Economics, 16(1), 213–252.

The problem set replicates the main results of the paper and covers:

- Panel data analysis
- Difference-in-Differences (DiD) estimation
- Cluster-robust standard errors
- Instrumental Variables (IV)


It investigates how real-time pollution monitoring can improve regulatory enforcement and reduce pollution.


## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("MuratSunmez/RTutorLessonsFromPollutionMonitoring")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorLessonsFromPollutionMonitoring)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorLessonsFromPollutionMonitoring")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorLessonsFromPollutionMonitoring",
       auto.save.code=TRUE, clear.user=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
