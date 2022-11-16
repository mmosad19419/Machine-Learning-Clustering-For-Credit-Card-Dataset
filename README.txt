## Clustering for Credit Cards dataset

I will apply my knowledge of clustering on the following dataset:

Dataset Link:
https://www.kaggle.com/datasets/arjunbhasin2013/ccdata

Clustering on this dataset will be done using KMeans, Hierarchal clustering and DBSCAN. Finding the optimal hypermaters for each and then choosing the best model among the three

### About the Dataset:

This case requires to develop a customer segmentation to define marketing strategy. Thesample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months.
The file is at a customer level with 18 behavioral variables.

## conclusion
### The optimal clustering technique for this dataset
1 - Agglomeritive Clustering  gives a resonable number of clusters __7__ with coherient clusters with silhouette score of __0.4__

2 - KMeans Clustering, gives a resonable number of clusters __6__ and the coherient clusters with silhouette score of __0.39__

3 - Desnisty Based Clustering, will not produce clusters, dbscan just make two groups, one group for outliers, and the rest of the data in the second group