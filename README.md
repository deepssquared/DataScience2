# Data Science II Assignments

During Spring 2019, for my Master of Public Health degree, I took a class in Data Science. Below are the homework assignments I completed, along with a quick overview of the skills and techniques employed.

## [Homework 1](https://github.com/deepssquared/ds2/blob/master/HW1.Rmd)
![hw1](https://github.com/deepssquared/ds2/blob/master/img/hw1.png | width=100)

For this exercise, I predicted solubility of compounds using their chemical structures. Among the 228 predictors, 208 are binary variables that indicate the presence or absence of a particular chemical substructure, 16 are count descriptors, such as the number of bonds or the number of bromine atoms, and 4 are continuous descriptors, such as molecular weight or surface area. The response is in the column “Solubility”.

* Fit a linear model using least squares and calculated the mean square error

* Fit a ridge regression model on the training data, with λ (chosen by cross-validation). 

* Fit a lasso model on the training data, with λ chosen by cross-validation. 

* Fit a PCR model on the training data, with M chosen by cross-validation. 

## [Homework 2](https://github.com/deepssquared/ds2/blob/master/HW2.Rmd)
![hw1](https://github.com/deepssquared/ds2/blob/master/img/hw2.png)

In this exercise, I built nonlinear models using the concrete compressive strength data set. The concrete compressive strength is a nonlinear function of age and ingredients. Ingredients include cement, blast furnace slag, ﬂy ash, water, superplasticizer, coarse aggregate, and ﬁne aggregate.

* Created scatter plots of response vs. predictors using the function featurePlot().

* Perform polynomial regression to predict compressive strength using water as the predictor.
  * Used cross-validation to select the optimal degree d for the polynomial. 
  * Make a respective plot

* Fit a smoothing spline using water as the predictor for a range of degrees of freedom 
  * Ploted the resulting ﬁts

* Fit a GAM using all the predictors. 

## [Homework 3](https://github.com/deepssquared/ds2/blob/master/Homework%203.Rmd)
![hw1](https://github.com/deepssquared/ds2/blob/master/img/hw3.png)
![hw1](https://github.com/deepssquared/ds2/blob/master/img/hw3_2.png)


This assignment uses Weekly data set, which is part of the ISLR package. It contains 1,089 weekly returns for 21 years, from the beginning of 1990 to the end of 2010.

* Produced some graphical summaries of the Weekly data.

* I used the following models to analyze the performance of the Lag predictors:
  * Logistic Regression
  * LDA
  * QDA
  * KNN
 
* Plotted the ROC curve using the predicted probability from logistic regression.

* Computed the confusion matrix and overall fraction of correct predictions.

## [Homework 4](https://github.com/deepssquared/ds2/blob/master/Homework_4.Rmd)
![hw4](https://github.com/deepssquared/ds2/blob/master/img/hw4.png)

This problem involves the Prostate data in the lasso2 package. Used set.seed() for reproducible results.

* Fit a regression tree with lpsa as the response and the other variables as predictors. Use cross-validation to determine the optimal tree size. Which tree size corresponds to the lowest cross-validation error? Is this the same as the tree size obtained using the 1 SE rule?

* Create a plot of the ﬁnal tree you choose. interpret the information displayed.

* Perform bagging and report the variable importance.

* Perform random forests and report the variable importance.

* Perform boosting and report the variable importance.

* Which of the above models will you select to predict PSA level? Explain.

This problem involves the OJ data in the ISLR package. The data contains 1070 purchases where the customers either purchased Citrus Hill or Minute Maid Orange Juice. A number of characteristics of customers and products are recorded. Create a training set containing a random sample of 800 observations, and a test set containing the remaining observations. Use set.seed() for reproducible results.

* Fit a classiﬁcation tree to the training set, with Purchase as the response and the other variables as predictors. Use cross-validation to determine the tree size and create a plot of the ﬁnal tree. Predict the response on the test data. What is the test classiﬁcation error rate?

* Perform random forests on the training set and report variable importance. What is the test error rate?

* Perform boosting on the training set and report variable importance. What is the test error rate?

## [Homework 5](https://github.com/deepssquared/ds2/blob/master/Homework_5.Rmd)
![hw5](https://github.com/deepssquared/ds2/blob/master/img/hw5.png)

This problem involves the OJ data set which is part of the ISLR package. The data con- tains 1070 purchases where the customer either purchased Citrus Hill or Minute Maid Orange Juice. A number of characteristics of the customer and product are recorded. Use set.seed() for reproducibility. Create a training set containing a random sample of 800 observations, and a test set containing the remaining observations.

* Fit a support vector classiﬁer (linear kernel) to the training data with Purchase as the response and the other variables as predictors. What are the training and test error rates?

* Fit a support vector machine with a radial kernel to the training data. What are the training and test error rates?

## [Homework 6](https://github.com/deepssquared/ds2/blob/master/Homework_6.Rmd)
![hw6](https://github.com/deepssquared/ds2/blob/master/img/hw6.png)

I used hierarchical clustering on the states using the USArrests data in the ISLR package. For each of the 50 states in the United States, the data set contains the number of arrests per 100,000 residents for each of three crimes: Assault, Murder, and Rape. The data set also contains the percent of the population in each state living in urban areas, UrbanPop. 

* Using hierarchical clustering with complete linkage and Euclidean distance, cluster the states. 

* Cut the dendrogram at a height that results in three distinct clusters. Which states belong to which clusters? 

* Hierarchically cluster the states using complete linkage and Euclidean distance, after scaling the variables to have standard deviation one. 

* What eﬀect does scaling the variables have on the hierarchical clustering obtained? In your opinion, should the variables be scaled before the inter-observation dissimilarities are computed?
