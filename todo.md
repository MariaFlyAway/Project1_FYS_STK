## Project 1

### a)
- DONE Generate data
- DONE Implement Franke function with noise
- DONE Write code for OLS up to fifth order - calculate MSE and R2
- DONE Plot MSE and R2 

- DONE Center and split data - TODO *discussion of how, why/why not for scaling*
- DONE Plot $\beta$-parameters - TODO *comment*
Figures for report: All beta-parameters

### b)
- DONE Implement Ridge method with Franke function with noise

- DONE Perform same analysis as above with different $\lambda$-values - TODO *study dependence*
- TODO *Compare to OLS*
Figures for report: last subplot of beta-parameters showing how lambda supresses beta-values


### c)
- DONE Implement Lasso method
- DONE Iterate over different lambda values
- note the intercept - scikit excludes
- *discuss the three models and which fits the data best*
Figures for report: last subplot of beta-parameters? Plots of (the best?) prediction with the data-points?

### d)
- DONE Derive the expected value and variance - done, needs explanations
- *Part of theory section*

### e)
- DONE make fig 2.11 Hastie
- DONE derive bias-variance tradeoff formula - TODO *include in theory-section*
-    explain what the terms mean and discuss their interpretations
- Perform a bias-variance analysis of the Franke by studying the MSE value as a function of the model complexity
and the ''number of datapoints''
- bootstrap-implementation - used for analysis and discussion
Figures for report: fig. 2.11 Hastie remake, 

### f)

- implement k-fold cross validation - scikit-learn - 5-10 folds
- evaluate the MSE function resulting from the test folds
- compare the MSE from cross-validation to MSE from bootstrap, comment results
- Ridge, Lasso and OLS

### g)

- download data
- prepare inputs to code


#### Priorities

Starting work on report