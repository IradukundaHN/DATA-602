## DATA 602 Assignment 5

### Objective
The main objective is to perform a simple linear regression modeling on the white wine quality.

### Dataset Description
The data consists of:
Input variables:
1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol
Target variable:
12 - quality (score between 0 and 10)
 
The dataset is a csv format, and it can be read directly from the data source: [UMBC's Small Dataset Repo](https://raw.githubusercontent.com/UMBC-Data-Science/DATA602Datasets/main/winequality-white.csv).
More information about the Wine Quality Dataset can be found from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality). 

### Business Question/Problem Statement
This is designed to model preferences on white wine quality based on physicochemical properties. With our dataset we can be able to determine the best predictors of white whine quality. We can also test our ability to make those predictions. This model could be used to understand what makes great wines and know how to dose each element accordingly.  

### Conclusions:
According to our analysis in the attached notebook, 
- We can explain about 98% of variance in the white wine quality values that fit our OSL regression model.
- The best predictors of white wine quality are such alcohol and volatile acidity, and the least drivers are citric acid and chlorides according to our standard regression model.
- There was no concerns about residuals.
- There was no indication of model overfitting our training dataset
- The regularization with Ridge regression on multiple alphas had no impact on our linear regression model.
