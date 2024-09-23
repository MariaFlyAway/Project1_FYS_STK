## Project 1

### a)
- Generate data from
- Implement Franke function with noise
- Write code for OLS up to fifth order - calculate MSE and R2
- Center and split data - discussion of how, why/why not for scaling
- Plot MSE and R2 
- Plot $\beta$-parameters - comment

### b)

- Implement Ridge method with Franke function
- Perform same analysis as above with different $\lambda$-values - study dependence
- Compare with a

### c)

- Implement Lasso method
- iterate over different lambda values
- note the intercept - scikit excludes
- discuss the three models and which fits the data best

### d)

- Derive the expected value and variance - done, needs explanations
- Part of theory section 

### e)

- make fig 2.11 Hastie
- derive bias-variance tradeoff formula - include in theory-section
- explain what the terms mean and discuss their interpretations
- Perform a bias-variance analysis of the Franke by studying the MSE value as a function of the model complexity
and the number of datapoints and 
- bootstrap-implementation - used for analysis and discussion

### f)

- implement k-fold cross validation - scikit-learn - 5-10 folds
- evaluate the MSE function resulting from the test folds
- compare the MSE from cross-validation to MSE from bootstrap, comment results
- Ridge, Lasso and OLS

### g)

- download data
- prepare inputs to code


## Report

__Figures and data to be included in report:__

### a)

__Results__: MSE and R2-score as a function of model compelxity for OLS<br>
__Discussion__: Critical discussion of why we chose to sclae/not scale our data

### b) 

__Results__: Same analysis as above but for different $\lambda$-values<br>
__Discussion__: Compare results with those from a). Study the dependence on $\lambda$

### c)

__Results__: Same analysis as above but for different $\lambda$-values <br>
__Discussion__: Compare results with those from a). Study the dependence on $\lambda$. Give a critical discussion of the three methods and a judgement of which model fits the data best. 

### d)

__Theory__: derivation of various properties

### e)

__Theory__: derivation of bias-variance tradeoff<br>
__Results__: reproduce figure 2.11 from Hastie, Tibshirani and Friedman. Bias-variance analysis of the Franke Function by studying the MSE value as a function of the complexity of the model.<br>
__Discussion__: discuss the bias and variance tradeoff as a function of the model complexity, number of datapoints and training and test data using the bootstrap resampling method. 

### f)

__Results__: MSE as a function resulting from the test folds<br>
__Discussion__: compare results from bootstrap, use 5-10 folds - OLS, Ridge and Lasso

### g)

All of the above
