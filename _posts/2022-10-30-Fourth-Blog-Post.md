**Feature Selection**

A dataset contain a lot of features which could be used for making predictions, however using all of the features would not result in perfect result and this we need to perform certain functions to use a subset of such features. With feature selection we can use things like transformation to compare various features and removing multicollinearity to reduce impact of similar type of variables

Feature Selection Methods

1. Forward Selection method: Forward selection is a kind of stepwise regression that starts with a blank model and gradually adds variables. You include the one variable that improves your model the most significantly in each step forward. 
Usually, a forward selection starts with just an intercept. The "best" variable where "best" is chosen by some predetermined criteria is included to the model after one tests the many potential relevant variables. 
We keep going through the process of adding one variable at a time and testing at each stage as the model continues to get better (per those same criteria). The procedure ends whenever there is no longer an improvement in the model with more variables.

2. Backward Elimination method: The converse of the forward selection is the backward elimination. With this approach, we first take into account all of the p variables before eliminating one at a time until the answer variable is estimated as accurately as possible. Based on the updated r-square values stated in the best subset selection, the best model is chosen.

3. Exhaustive Search: With this method, we must fit each of the two potential models, or distinct least square models, to every possible combination of the p predictors in the dataset. To select the best model, we can utilize CV/holdout, AIC/BIC, or both.

4. Lasso: Lasso is a regularization method . For a more accurate forecast, it is preferred over regression techniques. It imposes a penalty that is equivalent to the magnitude of the coefficient in absolute terms. With this type of regularization, sparse models with few coefficients may be produced. It's possible that some coefficients will go to zero and be dropped from the model. Coefficient values are closer to zero when the penalties are higher.

Conclusion: Method selection depends on the dataset. If the dataset has a lot of features forward or backward seelction method will be prefferred while when there are less features exhaustive search will yield better results. so its ideal to be flexible while chossing a feature selection technique. Along with EDA also helps in feature selection
