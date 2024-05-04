# Hybrid-Gaussian-Spectral-Clustering-HGSC-
A clustering algorithm that leverages Gaussian Mixture Models (GMM) and Spectral Clustering to identify and visualize clusters.

The main steps of the algorithm can be summarized as follows:

Clustering with GMM: A Gaussian Mixture Model is applied to the data to determine many initial local clusters of the data points. This step estimates a great number of Gaussian distributions, capturing the centers (means) and the spreads (covariances) of potential clusters.

Spectral Clustering on Distribution Means: Spectral Clustering is performed on the distribution centers (means) identified by the GMM. This step involves creating a distance matrix of the centers and then applying spectral clustering to partition these centers into groups based on their distances.

Aggregation of Covariances: For each identified cluster, the covariances of the components belonging to that cluster are aggregated. This step helps in understanding the overall spread and orientation of the clustered data points.
