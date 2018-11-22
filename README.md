# FIFA_Clustering

## Introduction

In the given notebook, I decided to conduct a exploratory data analysis on the results of different matches in FIFA Cup. 
The approach I went for was performing clustering on the data to see if the team perform similarly regardless of the 
team they're playing against. I perform this clustering under the assumption that the statistics provided in the dataset
are a measure of the performance of the team.

## Analysis Steps

The steps performed in this analysis:

* Reading Data
* Feature Engineering
    * Finding Missing Values
    * Categorical Encoding
    * Feature Correlation (Barplot, Heatmap)
* Kmeans, PCA and t-SNE
    * Finding the optimal number of clusters (Elbow Method)
* Plotting the clusters
    * using annotations for different teams
    * using colours for different clusters
    * using cluster centers to determine variance between clusters
