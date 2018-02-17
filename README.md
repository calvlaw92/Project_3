# Project_3

**Domain**<br/>
This problem is drawn from the analysis of the Boston housing dataset that was collected through a census done in 1970. As this was originally a study done to look at environmental economics before it was put into the UCI machine learning repository, there are many diverse studies that have been done on this dataset.<br/>

**Problem Statement**<br/>
In this study, we will use supervised learning to develop a multiple regression model to predict the median value of owner-occupied homes in $100s (medv) based on the following features: per capita crime rate by town (crim), proportion of owner-occupied units built prior to 1940 (age) and proportion of non-retail business acres per town (indus).<br/>

**Dataset and Input**<br/>
This dataset can be found from the UCI machine learning repository and also inbuilt as a dataset in R. The dataset contains 506 rows and 14 features which includes medv.<br/>

Features:<br/>
crim: per capita crime rate by town.<br/>
zn: proportion of residential land zoned for lots over 25,000 sq.ft.<br/>
indus: proportion of non-retail business acres per town.<br/>
chas: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).<br/>
nox: nitrogen oxides concentration (parts per 10 million).<br/>
rm: average number of rooms per dwelling.<br/>
age: proportion of owner-occupied units built prior to 1940.<br/>
dis: weighted mean of distances to five Boston employment centres.<br/>
rad: index of accessibility to radial highways.<br/>
tax: full-value property-tax rate per $10,000.<br/>
ptratio: pupil-teacher ratio by town.<br/>
black: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.<br/>
lstat: lower status of the population (percent).<br/>
medv: median value of owner-occupied homes in $1000s.<br/>

**Solution Statement**<br/>
The solution to this problem is to use a linear regression model in the form of a multiple linear regression to predict the median value of owner-occupied homes in $100s (medv) based on the following features: per capita crime rate by town (crim), proportion of owner-occupied units built prior to 1940 (age) and proportion of non-retail business acres per town (indus).<br/>

**Benchmark Model**<br/>
Given that we seek a regression model, a good naive benchmark would be to use the mean of medv, which is the dependent variable.<br/>

**Evaluation Metrics**<br/>
We will use the R-squared metric and the Root Mean Squared Error(RMSE) to measure the success of our model.
