# Read: Class 13

---

> [Back to Home](../README.md)

---

> [references](https://bigdata-madesimple.com/how-to-run-linear-regression-in-python-scikit-learn/)

## linear regression?

> What is it?

    is a popular technique and you might as well seen the mathematical equation of linear regression; WHich is like finding the best fit curve for a given set of data.

> Scikit-learn is a powerful Python module for machine learning. It contains function for regression, classification, clustering, model selection and dimensionality reduction. Today, I will explore the sklearn.linear_model module which contains “methods intended for regression in which the target value is expected to be a linear combination of the input variables”.

### examples

    import numpy as np
    import matplotlib.pyplot as plt
    import pandas as pd
    import seaborn as sns
    import sklearn
    import scipy.stats as stats

> convert boston.data into a pandas data frame.

        boston = pd.read_csv('boston.data', header=None)
        boston.columns = ['CRIM', 'ZN', 'INDUS', 'CHAS', 'NOX', 'RM', 'AGE', 'DIS', 'RAD', 'TAX', 'PTRATIO', 'B', 'LSTAT']
        boston.head()

        # CRIM      per capita crime rate by town

> Scikit Learn

    In this section I am going to fit a linear regression model and predict the Boston housing prices. I will use the least squares method as the way to estimate the coefficients.

    Y = boston housing price(also called “target” data in Python)

    and

    X = all the other features (or independent variables)

    First, I am going to import linear regression from sci-kit learn module. Then I am going to drop the price column as I want only the parameters as my X values. I am going to store linear regression object in a variable called lm.

---

    from sklearn.linear_model import LinearRegression
    X = boston.drop('PRICE', axis=1)

    # This creates a linear regression object that can be used to make predictions.
    lm = LinearRegression()
    lm

> If you want to look inside the linear regression object, you can do so by typing LinearRegression. and the press **<tab\>** key. This will give a list of functions available inside linear regression object.

---

> Important functions to keep in mind while fitting a linear regression model are:

lm.fit() -> fits a linear model

lm.predict() -> Predict Y using the linear model with estimated coefficients

lm.score() -> Returns the coefficient of determination (R^2). A measure of how well observed outcomes are replicated by the model, as the proportion of total variation of outcomes explained by the model.

You can also explore the functions inside lm object by pressing lm.<tab\>

---

Conclusion
To recap what I have done till now,

    I explored the boston data set and then renamed its column names.
    I explored the boston data set using .DESCR, my goal was to predict the housing prices using the given features.
    I used Scikit learn to fit linear regression to the entire data set and calculated the mean squared error.
    I made a train-test split and calculated the mean squared error for my training data and test data.
    I then plotted the residuals for my training and test datasets.

---

> [Back to Home](../README.md)
