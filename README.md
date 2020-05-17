# DataScience
A repo for all my Data-Science ipynbs<br><br>

Imports used:
<i>
```diff
+ from sklearn.linear_model import LinearRegression
+ from sklearn.feature_selection import f_regression
+ from sklearn.model_selection import train_test_split
+ from sklearn.preprocessing import StandardScaler
+ from statsmodels.stats.outliers_influence import variance_inflation_factor
+ import numpy as np
+ import pandas as pd
+ import matplotlib.pyplot as plt
+ import statsmodels.api as sm
+ import seaborn as sns
```
</i>  
<b>0 Percentile Rank</b><br>
Contains the rank statistics of my fellow classmates

<b>1 First Regression Model</b><br>
Contains the SAT-GPA score prediction using sklearn, statsmodels. I've used the OLS model.

<b>2 First Multiple Regression</b><br>
What measures you should take before performing the multiple regression? (any regression!)

<b>3 Multiple Regression w Categorical Data</b><br>
Multiple Regression with Categorical Data using dummy variables. Also, predicted the result with the help of StatsModels.api.
(Nothing ML here. Just basic estimations!)

<hr>
Basic ML starts from here...
<br><br>

<b>4 Simple Linear Regression w sklearn</b><br>
This file shows the differences between statsmodels and sklearn. How we have to define r-squared, intercept & coeffecient seperately to create statsmodels like summary.

<b>5 Multiple Regression w sklearn</b><br>
This file shows the regression, r-squared, the adjusted r-squared, feature selection, standardization, regression with scaled inputs, predicting, and getting to know sklearn little deeper!

<b>6 Train-Test in Sklearn</b><br>
Using the function train_test_split() provided by sklearn.model_selection

<b>7 Real life eg. Car Data</b><br>
Performing the prediction on real life dataset. From preprocessing (removing missing values, exploring probability sistribution functions, dealing with outliers, checking OLS assumptions, multicollinearity, dummy varibales) 
to Performing the Regression (scaling, spliting, weights & biases) and then Testing. All on sklearn.
