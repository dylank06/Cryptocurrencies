# Cryptocurrencies

## Summary 

Used unsupervised machine learning techniques to analyze cryptocurrency data. Worked primarily with the K-means algorithm, the main unsupervised algorithm that groups similar data into clusters. Also implemented principal component analysis (PCA), which employs many different features. Preprocessed data for unsupervised learning, Clustered data using the K-means algorithm, and Determined the best amount of centroids for K-means using the elbow curve.

## Overview 

### Preprocessed the Data for PCA

Used knowledge of Pandas, to preprocess the dataset in order to perform PCA. 

### Reduced Data Dimensions Using PCA

Used knowledge of how to apply the Principal Component Analysis (PCA) algorithm, reduced the dimensions of the crypto DataFrame to three principal components and placed these dimensions in a new DataFrame.

### Clustering Cryptocurrencies Using K-means

Used knowledge of the K-means algorithm, to create an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame. Then, used the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

### Visualizing Cryptocurencies Results 

Used knowledge of creating scatter plots with Plotly Express and hvplot, visualized the distinct groups that correspond to the three principal components, then created a table with all the currently tradable cryptocurrencies using the hvplot.table() function.

