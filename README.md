# Clustering

GaussianClusterData has been taken from the UCI Machine Learning Data repositoy and is utilized for performing different types of clustering on it.
Given data has been plotted on a 2D grid by using the Matplot lib python package.

1. K-Means Clustering:
  By varying the size of cluster the Kmeans clustering is performed using the python's sklearn Kmeans cluster method.
  Silhouette Coefficient and BIC have been evaluated for each cluster size and best clustering is determined based on the values of silhouette  coefficient and BIC.
  Silhouette plot has been drawn and best value is determined against the size of clusters.
  BIC values are plotted against the size of clusters and the best value is determined from the plot.
  Plot of the data for best Kmeans model has been drawn and the incorrectly grouped data are highlighted.
  
2. Agglomerative Clustering - Single Linkage:
  As there are no readily available sklearn methods for single linkage clustering, a different approach has been used.
  Single Linkage is initially created using the Sklearn linkage method.
  Using cut tree method data has been cut into the specified number of clusters.
  Dendrogram for the resultant data set has been drawn using the scipy library.
