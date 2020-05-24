# DataScience
A repo for all my Data-Science ipynbs. Helpful for someone who wants to start the basics of Data Science (Stats, ML, DL). <br>
All datasets (*.csv) are provided by [365datascience]. <br><br>


Imports used:  
<i>
```diff

+ import numpy as np
+ import pandas as pd
+ import matplotlib.pyplot as plt
+ import statsmodels.api as sm
+ import seaborn as sns
+ from sklearn.linear_model import LinearRegression
+ from sklearn.feature_selection import f_regression
+ from sklearn.model_selection import train_test_split
+ from sklearn.preprocessing import StandardScaler
+ from statsmodels.stats.outliers_influence import variance_inflation_factor
+ from sklearn.cluster import KMeans
+ from sklearn import preprocessing
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
Performing the prediction on real life dataset. From preprocessing (removing missing values, exploring probability sistribution functions, dealing with outliers, checking OLS assumptions, multicollinearity, dummy variables) 
to Performing the Regression (scaling, spliting, weights & biases) and then Testing. All on sklearn.

<b>8 Simple Logistic Regression</b><br>
Logistic Regression; plotting and summary table from StatsModels.

<b>9 Logistic Regression Binary Predictors</b><br>
Logistic Regression Binary Predictors with StatsModels; Regression, Confusing-Matrix, Testing with test data.

<b>10 Cluster Analysis</b><br>
Using KMeans clustering to generate continents where each data point is a country.

<b>11 Cluster Analysis w Categorical Data</b><br>
Using KMeans clustering to generate continents where language, continents are dummy variables.

<b>12 Clusters with WCSS, Elbow method</b><br>
Within Clusters Sum of Squares(WCSS). How elbow method can be used to determine the clusters. (And, how sklearn uses kmeans++ by default)

<b>13 Cluster Analysis Market Segmentation</b><br>
Using standardization on real life data to see how clusters are changing.

<b>14 Heatmaps & Dendogram</b><br>
Seaborn magic! 

<hr>
Basics of Deep Learning starts from here...<br>
Before jumping onto the next section, learn the basics of numpy array, tensors, matrices, operations on matrices(addition, subtraction, transpose, dot product)
(In terms of programming, tensor is no different than ndarray.)
<br><br>

<b>15 Neural Networks, training the model</b><br>
will upload soon


[365datascience]: https://365datascience.com/
