
## CPSC 392
## Introduction to Data Science
## Assignment 04
## Due: March 18th, 2020 02:30pm
## 100 points

Let's apply Logistic Regression to solve a real world problem. A winery has hired you to come up with a way to predict a wine's quality using its chemical contents. The quality level goes from 3 (lowest) to 8 (highest). Fit a logistic regression model on the data that is able to predict the wine quality using one or more independent variables. 

To support your model performance, show its accuracy (using the accuracy_score function), show the confusion matrix generated and write a short note interpreting the confusion matrix.

The owner of the winery also wants you to do a binary classification using logistic regression. It is up to you to come up with a cutoff value for the quality. You could do quality levels 3 and 4 in one group, and the rest in the other, and say you are trying to classify bad wines from the others etc. To evaluate this model, you should again show the confusion matrix with a short note interpreting it, and print the accuracy, recall, and precision scores. 

I recommend trying different combinations of attributes to get the best accuracy for your model. Make sure to use a training and test set with 80/20 split for both models.

Present your code, findings, comments, and plots in a  Jupyter notebook file. Don't forget to attach a README with your code files and submit a compressed folder to Blackboard before 2:30pm on 18th March, 2020.

