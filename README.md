# clustering_algorithms

## Loan allocation

Continuing on the loan allocation problem, it is eminent that alternative machine learning methods be employed that do not necessarily require
supervision to predict the likelihood of a customer paying or defaulting on their loan.

Herein, we shall employ several clustering technique to previously used data to try and ascertain this likelihood.

## Modelling Approaches

Our modelling approach intends to create a clustering model that can perform well with at most four categorical clusters each for a credit score between 0 and 1.

### Base Models

For this projects, based models were developed and fitted on a contrived data set.
These were; affinity propagation, agglomerative clustering, BIRCH, DBSCAN, gaussian mixture, k_means,
mean_shift, mini batch k means, OPTICS and spectral clustering.

The intend, if to find which of these models will best fit our data and give definitive clusters for our statement problem.

### K Means Clustering

The first model - performed averagely, but was unable to give an anticipated definitive outcome. Scored an
inertia value of 4406 with a minimum of 7 clusters.

### Affinity Propagation clustering

Predicted two distinct cluster but imbalanced clusters both for the original dataset and the synthetically generated data. The synthetic data created a more distinct clustering.

### Agglomerative Clustering

Predicted two less distinct clusters for the original data. Predicted clusters were more distinct on the synthetic data.

### BIRCH clusterinng

Predicted two less distinct clusters for the original dataset. Predicted more distict clusters on the synthetic data.

## Other Clusters

Other clusters deployed in this project that did not perform well on creating or identifying proper clusters: OPTICS, K-means, mini-batch-k-means, mean-shift and spectral clustering.
