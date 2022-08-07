# Clustering

Clustering analysis is an unsupervised learning method that separates the data points into several specific bunches or groups, such that the data points in the same groups have similar properties and data points in different groups have different properties in some sense.

It comprises of many different methods based on different distance measures. E.g. K-Means (distance between points), Affinity propagation (graph distance), Mean-shift (distance between points), DBSCAN (distance between nearest points), Gaussian mixtures (Mahalanobis distance to centers), Spectral clustering (graph distance), etc.

There are different approaches and algorithms to perform clustering tasks which can be divided into three sub-categories:

- **Partition-based clustering:** E.g. k-means, k-median
- **Hierarchical clustering:** E.g. Agglomerative, Divisive
- **Density-based clustering:** E.g. DBSCAN

## Libraries

| Title | Description, Information |
| :---:         |          :--- |
|[HDBSCAN](https://hdbscan.readthedocs.io/en/latest/index.html#)|The hdbscan library is a suite of tools to use unsupervised learning to find clusters, or dense regions, of a dataset. The primary algorithm is HDBSCAN* as proposed by Campello, Moulavi, and Sander. The library provides a high performance implementation of this algorithm, along with tools for analysing the resulting clustering.|
|[]()| |

## Determine the optimum number of clusters

There are various methods to determine the optimum number of clusters, i.e. Elbow method, Average Silhouette method.
