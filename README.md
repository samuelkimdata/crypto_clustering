# CryptoClustering - Module 19 Challenge

# Overview
This challenge required the use of unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

# Technologies
* Pandas
* SciKit Learn

# Prepare the Data
A Dataframe with the "coin_id" set as the index was created once the "StandardScaler()" and "scikit-learn" was used to normalize the data in the CSV file.
<img width="1523" alt="Screenshot 2023-12-19 at 3 05 38 PM" src="https://github.com/samkimmmm/CryptoClustering/assets/135805393/9a5204e2-3e0c-4314-bcb0-b624798dc5fa">

## The best value for K was found by creating an empty list to store the inertia values. The results were then plotted on an hvplot.
<img width="1266" alt="Screenshot 2023-12-19 at 3 06 51 PM" src="https://github.com/samkimmmm/CryptoClustering/assets/135805393/cdc46970-dd1a-481f-b98b-4a2926048c9c">

## Clusters were then predicted to cluster the cryptocurrencies into groups. The results were then plotted on a scatter plot with the x-axis set to "PC1" and the y-axis set to "PC2".
<img width="1232" alt="Screenshot 2023-12-19 at 3 09 40 PM" src="https://github.com/samkimmmm/CryptoClustering/assets/135805393/82a1d807-6b21-4ce0-8e91-b61d3cb8ee2b">

## A Principal Component Analysis (PCA) was performed to reduce the features to 3 principal components.
### What is the total explained variance of the three principal components? 89.50
