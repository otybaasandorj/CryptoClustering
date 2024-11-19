# CryptoClustering

To predict if cryptocurrencies are affected by 24-hour or 7-day price changes, unsupervised learning techniques such as K-Means clustering were applied to group cryptocurrencies based on their price change patterns, and Principal Component Analysis (PCA) was used to reduce dimensionality, simplifying the analysis while retaining critical variability in the data. The goal of the assignment was to perform K-Means clustering on cryptocurrency data to group them based on price changes (24-hour and 7-day periods), use principal component analysis (PCA) to reduce the dimensionality of the dataset while preserving most of the variability, and compare the clustering results before and after applying PCA to determine the impact of dimensionality reduction.

PCA reduced the number of features from 6 to 3 while retaining approximately 90% of the total variance (as shown in the explained variance ratio). This reduction simplified the dataset and improved clustering efficiency while preserving most of the important information. Both the original data and PCA-reduced data resulted in 4 clusters with similar grouping patterns. 

![clusters.png](https://github.com/otybaasandorj/CryptoClustering/blob/main/images/clusters.png)

