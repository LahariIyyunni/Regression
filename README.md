# SimpleRegression


Simple Linear Regression
Multiple Linear Regression
Polynomial Regression
Support Vector for Regression (SVR)
Decision Tree Classification
Random Forest Classification

For Simple Linear Regression - linear_model module class is LinearRegression
only fit is used here

To predict the test values - we use predict class
predict always expects a 2D array

LR.predict([[12]])
[[12]] makes it a 2D

from sklearn.linear_model import LinearRegression
LR=LinearRegression()
LR.fit(X_train,Y_train)

