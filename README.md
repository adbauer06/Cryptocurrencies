# Cryptocurrencies

## Project Overview
The purpose of this project was to create an analysis to present to clients who are preparing to enter the cryptocurrency market.  A report was created that includes what cryptocurrencies are on the trading market and how they can be grouped to create a classification system.  An unsupervised learning model was used to analyze the data, along with a clustering algorithm.  Visualizations were then created to present the findings.

## Analysis Summary
The following steps were taken to create this analysis
1. A dataset containing cryptocurrency information was downloaded from CryptoCompare
2. The data was then preprocessed to remove unnecessary data, clean up records with null values, convert text values to numeric, and scale the data.
3. Data dimensions were reduced using the Principal Component Analysis (PCA) algorithm
4. The cryptocurrencies were then clustered using the K-means algorithm and a new dataframe was created integrating the cluster and predictions data.
5. Visualizations were then created including:
    - A 3D Scatter plot showing the cluster data
    - A table showing tradable cryptocurrencies
    - A scatter plot showing TotalCoinSupply and TotalCoinsMined by coin name
