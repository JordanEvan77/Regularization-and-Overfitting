# Regularization-and-Overfitting
Looking at a comparison of a large polynomial and LASSO Regression, overfitting and error

OBSERVING THE FINAL LAYERED GRAPH:
After implementing the LASSO regression in the iterative loop there is much less error fluctuation between train and test. They are the flat yellow and blue lines for LASSO. This is because there is an increased bias on the error created by lasso, but it is far more stable. (yellow is train error LASSO, Green is train error Polynomial, blue is test error LASSO, red is test error Polynomial). We see at the inflection point between 2 and 4, that we begin to overfit pretty severely for the red curve and that we begin to have a poorer performance with the test data, even though the train error is improving. Despite LASSO’s bias (causing initial slight increase in error) we do not experience this overfit at any point. 
