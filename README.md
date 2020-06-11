# Data Science II Assignments

During Spring 2019, for my Master of Public Health degree, I took a class in Data Science. Below are the homework assignments I completed, along with a quick overview of the skills and techniques employed.

## [Homework 1](https://github.com/deepssquared/ds2/blob/master/HW1.Rmd)

For this exercise, I predicted solubility of compounds using their chemical structures. Among the 228 predictors, 208 are binary variables that indicate the presence or absence of a particular chemical substructure, 16 are count descriptors, such as the number of bonds or the number of bromine atoms, and 4 are continuous descriptors, such as molecular weight or surface area. The response is in the column “Solubility”.

* Fit a linear model using least squares and calculated the mean square error

* Fit a ridge regression model on the training data, with λ (chosen by cross-validation). 

* Fit a lasso model on the training data, with λ chosen by cross-validation. 

* Fit a PCR model on the training data, with M chosen by cross-validation. 

## [Homework 2](https://github.com/deepssquared/ds2/blob/master/HW2.Rmd)

In this exercise, I built nonlinear models using the concrete compressive strength data set. The concrete compressive strength is a nonlinear function of age and ingredients. Ingredients include cement, blast furnace slag, ﬂy ash, water, superplasticizer, coarse aggregate, and ﬁne aggregate.

* Created scatter plots of response vs. predictors using the function featurePlot().

* Perform polynomial regression to predict compressive strength using water as the predictor.
  * Used cross-validation to select the optimal degree d for the polynomial. 
  * Make a respective plot

* Fit a smoothing spline using water as the predictor for a range of degrees of freedom 
  * Ploted the resulting ﬁts

* Fit a GAM using all the predictors. 

## [Homework 3](https://github.com/deepssquared/ds2/blob/master/Homework%203.Rmd)

## [Homework 4](https://github.com/deepssquared/ds2/blob/master/Homework_4.Rmd)

## [Homework 5](https://github.com/deepssquared/ds2/blob/master/Homework_5.Rmd)
