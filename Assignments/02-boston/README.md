## CPSC 392
## Introduction to Data Science
## Assignment 03
## Due: March 4th, 2020 02:30pm
## 100 points

1. Write a Python program to compute the best-fit line for a set of data points using linear regression. The code should be written in pure Python and you do not need additional libraries (except math). Make your program modular so you end up with a single function called LM(x,y) that takes two lists of numbers as parameters. Here list x will be the list of independent variables and list y will be the list of dependent variables. Your function should output the best fit line “y = b0 + b1x” and the coefficient of determination (r2). Lastly, the function should also plot the data as a scatter plot along with the best fit line. (50)

To test your code, you may use x = [3,7,4,1,5] and y = [7,10,6,4,8]. 


2. Predict the median value of homes in Boston using a linear regression model. You will use the boston.csv data (both provided here and on Blackboard) and find one independent variable you think is the best predictor for the medv (median value) column. You will test your model using a 70/30 split and show the final R-squared value. (50)

* 'crim': per capita crime rate by town.
* 'zn': proportion of residential land zoned for lots over 25,000 sq.ft.
* 'indus': proportion of non-retail business acres per town.
* 'chas':Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).
* 'nox': nitrogen oxides concentration (parts per 10 million).
* 'rm': average number of rooms per dwelling.
* 'age': proportion of owner-occupied units built prior to 1940.
* 'dis': weighted mean of distances to five Boston employment centres.
* 'rad': index of accessibility to radial highways.
* 'tax': full-value property-tax rate per $10,000.
* 'ptratio': pupil-teacher ratio by town
* 'black': 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.
* 'lstat': lower status of the population (percent).
* 'medv': median value of owner-occupied homes in $$1000s

For 10 extra points, generate a multiple linear regression using more than 1 independent variables.

For this assignment, you will submit 2 Python notebooks, simple-regression.ipynb and boston-regression.ipynb. Present your code, findings, comments, and plots in the notebook files. Don't forget to attach a README with your code files and submit a compressed folder to Blackboard before 2:30pm on 4th March, 2020.
