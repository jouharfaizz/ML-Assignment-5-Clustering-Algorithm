# ML-Assignment-5-Clustering-Algorithm
Iris Dataset Clustering Assignment
Overview

This project demonstrates the application of two clustering algorithms—KMeans and Hierarchical Clustering—on the Iris dataset from the sklearn library. The objective is to group the Iris flowers into clusters based on their features (sepal and petal length/width) and visualize the resulting clusters.
Dataset

The Iris dataset contains 150 samples of iris flowers, each with 4 features:

    Sepal Length
    Sepal Width
    Petal Length
    Petal Width

There are 3 species of iris flowers in the dataset: Iris-setosa, Iris-versicolor, and Iris-virginica, though the species information is not used for clustering.
Key Components
1. Loading and Preprocessing

The dataset is loaded using the sklearn load_iris() function, and the species column is dropped since it is not needed for clustering.
2. Clustering Algorithms
A) KMeans Clustering

    Description: KMeans clustering partitions the dataset into a pre-specified number of clusters (k) by minimizing the distance between data points and their corresponding cluster centroids.
    Application: KMeans clustering was applied to the Iris dataset with 3 clusters (corresponding to the 3 species of flowers). The clusters are visualized using a scatter plot of the first two features (sepal length and sepal width).

B) Hierarchical Clustering

    Description: Hierarchical clustering builds a tree-like structure of clusters. In this implementation, agglomerative hierarchical clustering is used to group samples iteratively, merging small clusters into larger ones.
    Application: Agglomerative clustering was applied to the Iris dataset, resulting in 3 clusters. A scatter plot was used to visualize the clustering results.

3. Visualization

Both clustering algorithms' results are visualized using scatter plots, where the data points are color-coded based on the predicted cluster labels.
