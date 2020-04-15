## CPSC 392
## Introduction to Data Science
## Assignment 05
## Due: April 20th, 2020 02:30pm
## 100 points

1) Synthetic data sets are created to test the power and abilities of different algorithms. One such data set, set1.txt is made of 5000 2D data points and can be used to test some clustering algorithms. You can directly plot the data set to see how many clusters there are. But let's use a dendrogram (from the scipy library) to see if we are able to find a cutoff distance value where all clusters are viewable. Next, using the built-in agglomerative hierarchical clustering algorithm in the sklearn library, cluster the data and show a scatter plot based with colored by the cluster labels.

2) If you recall, the red-wine data set had different features of a wine along with its quality. There were 6 quality levels in total. Let's see if we can cluster them separately too. You will remove the quality attribute, and run PCA to reduce the feature space to 2 features only. Next, you can create a dendrogram and use agglomerative clustering to find clusters in the data. You will then display a scatter plot of the 2 principal components, with points colored by their generated clusters.

Present your code, findings, comments, and plots in a  Jupyter notebook file. Don't forget to attach a README with your code files and submit a compressed folder to Blackboard before class on 20th April, 2020.
