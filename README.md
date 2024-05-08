# CryptoClustering-Challenge

# Module 19 Challenge

## Overview
This project involves clustering cryptocurrency market data to uncover patterns and group similar cryptocurrencies using machine learning techniques (unsupervised learning). The analysis includes standardizing the data, applying K-Means clustering, optimizing the clustering with PCA (Principal Component Analysis), and comparing results with and without PCA.

## Prerequisites
Before running this project, ensure you have the following installed:
- Python 3.8+
- Pandas
- hvPlot
- scikit-learn

## Instructions

1. Load the dataset:
    - Ensure your dataset crypto_market_data.csv is in the Resources directory.
    - The dataset should include various features of cryptocurrencies that are relevant for clustering, like price changes.

2. Run the script:
    - Execute the Python script to perform the analysis. The script will automatically load data, process it, and display visual results.

## Key Components of the Script
- Data Loading and Preprocessing: Standardize the market data to normalize the scale of the features.
- Clustering with K-Means: Apply K-Means clustering to the standardized data to identify groups of similar cryptocurrencies.
- Optimization with PCA: Reduce the dimensionality of the data using PCA to improve clustering performance.
- Elbow Method Analysis: Use the elbow method to determine the optimal number of clusters both with and without PCA.
- Visualization: Visualize clustering results and compare the effectiveness of PCA in the clustering process.

## Conclusion
This analysis allows us to visually and quantitatively assess the impact of PCA on the clustering of cryptocurrencies. It helps determine whether the reduction of dimensionality improves the clustering outcome by comparing elbow plots and the distribution of clusters in feature space.