***
# Classification and Variable Selection Exercise
***

**To read a version of the notebook, wihout needing to install RStudio, a .pdf is available.** 

This exercise is a **Classification** problem, with target variable having two levels (-1 and 1) and a high number of candidates for explanatory variables. **Variable selection** is performed using Random Forests with the **VSURF** package. Out of a couple of hundreds of variables, only a few are shown to be relevant. Predictions are then made using **Logistic Regression** and **Classification Tree** models, which are compared by calculating accuracy.

# Installation

RStudio 2023.09.1+494 was used, available for download and installation <a href="https://dailies.rstudio.com/version/2023.09.1+494/" target="_blank">here</a>. R version was 4.2.3.

To install required packages from .lock file, use the command **renv::restore()**.
