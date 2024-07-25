# Linear regression

Welcome to the repository for understanding and setting up a linear regression model. In this repository, we aim to provide a comprehensive guide on the key assumptions that must be met to ensure the validity and reliability of a linear regression model.

## Assumptions of Linear Regression
To set up a linear regression model correctly, it is essential to ensure that the following assumptions are respected:

  - Linear Relationship:
There should be a linear relationship between the dependent variable and the independent variables.

Fixing solution : [The variables transformation to linearize the model](https://github.com/ramandrosoa/Linear-Regression/blob/main/R%20file/Transformation-to-linearize-the-model.md) 
  
  - Homoscedasticity:
The variance of the error terms should be constant across all levels of the independent variables. This means the error term $\varepsilon_i$ should be the same for any $i$. 

Fixing solution : [The weighted least squares](https://github.com/ramandrosoa/Linear-Regression/blob/main/R%20file/Weighted-Least-Squares.md) , [the variance stabilizing](https://github.com/ramandrosoa/Linear-Regression/blob/main/R%20file/variance_stabilizing.md)
  
  - Uncorrelated error terms:
The covariance of $\varepsilon_i$ and $\varepsilon_j$, for $i\neq j$, should be 0.

Fixing solution : [The variables transformation to handle autocorrelation](https://github.com/ramandrosoa/Linear-Regression/blob/main/R%20file/autocorrelation.md)
  
  - Normality of Errors:
The error terms $\varepsilon_i$ should follow a Gaussian distribution.

Fixing solution : [The Box-Cox transformation](https://github.com/ramandrosoa/Linear-Regression/blob/main/R%20file/Box_Cox.md)
  
  - Linear Independence of the Regressors:
The regressors should not be highly correlated to each other.

Fixing solution : [The Ridge regression](https://github.com/ramandrosoa/Linear-Regression/blob/main/R%20file/Multicollinearity-part1.md) , the variables selection
   

## Importance of These Assumptions
These assumptions are crucial because they ensure the validity and reliability of the results obtained from the regression model. When these assumptions are met:

  - Statistical Inference: The results from the model can be used to make valid inferences about the population.
  - Reliable Prediction: The model can provide reliable predictions for the dependent variable.
  - Interpretability: The coefficients of the model are interpretable and meaningful.

## Diagnosing Assumption Violations and Remedial Measures
While no model perfectly meets all assumptions, it is important to understand and diagnose any violations. Identifying these violations can help in informing about the model's validity and making necessary adjustments to the model or using alternative approaches to handle the violations. 

## References

  - MATH 764 Linear Regression, Illinois Institute of Technology 
  - MATH 765 Model diagnostics, Illinois Institute of Technology
  - Journal of Applied Statistics, S.Chinn
  - [Maximum Likelihood Estimation, Imperial College London](https://www.ma.imperial.ac.uk/~das01/MyWeb/M2S1Previous/2004/Handouts/Mle.pdf)
  - [Mathematics for Machine Learning and Data Science, DeepLearning.AI](https://www.coursera.org/specializations/mathematics-for-machine-learning-and-data-science)






