## CPSC 392
## Introduction to Data Science
## Assignment 06
## Due: April 13th, 2020 02:30pm
## 100 points

Do you think you are an audiophile and are able to classify different genres of music? Well you can do the same using a clustering algorithm! Machine Learning FTW!! 

The songs.csv file contains different features of songs from X different music genres. Your task is to use the built-in kMeans clustering algorithm in the scikit-learn library to find the hidden genres in the data. You can use the elbow method to first figure out how many genres there should be, and then come up with a way to reduce the number of attributes you are using for clustering. The idea here is to find out which property of a song is best in distinguishing different genres. 

Once done, add a lengthy note about how you would go about validating the findings from your model.

Next, since we haven't done a lot of pure Python coding, I want you to also write your own k-Means algorithm. There are plenty of implementations for kMeans on the internet. But please use them as inspiration to write your own code. To make things easy, your kMeans algorithm function can only use the k value of 2, and can be applied on 2 independent variables. I am leaving the implementation open ended so your independent variables can be in the form of a data frame, lists, etc. The convergence mechanism for your centroids is also left open ended, and you can choose any tolerance value for your function. Please don't forget to add comments to your code.



Present your code, findings, comments, and plots in a  Jupyter notebook file. Don't forget to attach a README with your code files and submit a compressed folder to Blackboard before midnight on 13th April, 2020.
