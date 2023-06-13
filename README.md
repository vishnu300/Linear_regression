# Linear_regression
Linear regression multiple variable


Linear regression is a widely used algorithm in machine learning for predicting continuous numerical values based on input features. It assumes a linear relationship between the input variables (also known as independent variables or features) and the output variable (also known as the dependent variable or target).

The goal of linear regression is to find the best-fitting line that minimizes the difference between the predicted values and the actual values. The line is represented by an equation of the form:

y = mx + b

Where:
- y is the dependent variable (target)
- x is the independent variable (feature)
- m is the slope of the line
- b is the y-intercept

The linear regression algorithm aims to find the optimal values for the slope (m) and the intercept (b) that minimize the sum of squared differences between the predicted and actual values. This process is typically achieved using optimization techniques such as ordinary least squares (OLS) or gradient descent.

Linear regression can be extended to multiple input variables, resulting in multiple linear regression. In this case, the equation becomes:

y = b0 + b1*x1 + b2*x2 + ... + bn*xn

Where:
- y is the dependent variable (target)
- x1, x2, ..., xn are the independent variables (features)
- b0 is the y-intercept
- b1, b2, ..., bn are the coefficients for each feature

To train a linear regression model, you need a labeled dataset that consists of input feature values and corresponding target values. The model estimates the optimal values for the coefficients (b0, b1, ..., bn) based on the training data, allowing it to make predictions on new, unseen data.

Linear regression is a simple and interpretable algorithm but assumes a linear relationship between the variables. If the relationship is not linear, more complex models like polynomial regression or nonlinear regression may be more suitable.
to using predict house price 