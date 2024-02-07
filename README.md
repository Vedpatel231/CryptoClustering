# Cryptocurrency Clustering with K-Means and PCA

## Overview
This project groups cryptocurrencies according to market data by using K-Means clustering. By dividing the dataset into discrete groups, the aim is to find patterns and connections in the data. Two methods were used: Principal Component Analysis (PCA)-based clustering following dimensionality reduction and clustering utilizing the original characteristics.

## Process
The dataset comprised various price change percentages over different time frames for numerous cryptocurrencies. The following steps were taken to achieve the clustering:

- Applied `StandardScaler` to normalize the feature set, ensuring that each feature contributed equally to the analysis.
- Determined the optimal number of clusters (`k`) by plotting the elbow curve and identifying the point of inflection.
- Implemented K-Means clustering using the optimal `k` to categorize the cryptocurrencies into clusters based on the original normalized data.
- Reduced the dimensionality of the data to three principal components and repeated the K-Means clustering to compare results.
- Visualized the clusters using `hvPlot` scatter plots, contrasting the clustering on the original and reduced feature spaces.
- Examined the impact of using fewer features on the clustering outcomes, assessing aspects like cluster separation, computational efficiency, and interpretability.

## Conclusion
The project effectively grouped cryptocurrency and illustrated how dimensionality reduction affects K-Means clustering. By highlighting the trade-offs between computing efficiency and cluster interpretability, it sheds light on the correlations and structure found in the data related to the bitcoin market.
