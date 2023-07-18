# Prediction of Optimum Number of Clusters using Unsupervised ML

This repository contains the solution for Task 2 of the GRIP (The Sparks Foundation) Data Science and Business Analytics Internship. The task aims to predict the optimum number of clusters in the 'Iris' dataset and represent it visually.

## Dataset
The 'Iris' dataset used for this task can be accessed from the following link: [Dataset Link](https://bit.ly/3kXTdox)

The 'Iris' dataset is a widely used dataset in the field of machine learning. It consists of measurements of different features of Iris flowers, such as sepal length, sepal width, petal length, and petal width. The goal of this task is to apply unsupervised learning techniques to determine the optimal number of clusters within the dataset.

## Approach
To accomplish this task, the following steps are followed:

1. Import the necessary libraries: pandas, numpy, matplotlib, and sklearn.
2. Load the 'Iris' dataset from the sklearn.datasets module using the provided link.
3. Create a pandas dataframe from the dataset to facilitate data analysis.
4. Scale the data using the StandardScaler from sklearn.preprocessing to ensure all features are on a similar scale.
5. Use the elbow method to determine the optimal number of clusters for k-means clustering. The elbow method helps identify the number of clusters that minimizes the within-cluster sum of squares.
6. Fit the k-means clustering model using the optimal number of clusters obtained from the elbow method.
7. Visualize the clusters using a scatter plot to observe the separation of data points among different clusters.
8. (Optional) Compare the predicted clusters with the actual target labels, if available, to evaluate the performance of the clustering algorithm.

Feel free to explore the code provided in the repository and modify it as needed. If you have any questions or suggestions, please don't hesitate to contact me.

## Author
- Name: Aboubakr Aakou
