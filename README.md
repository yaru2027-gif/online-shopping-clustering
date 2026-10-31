# Online Shopping Behavior Clustering

This project explores online shopping behavior using K-Means clustering and the Online Shoppers Purchasing Intention Dataset from the UCI Machine Learning Repository.

## Research Question

Can online shopping sessions be divided into different groups based on browsing behavior, and do these groups have different purchase rates?

## Dataset

Source: https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset

The dataset contains 12,330 online shopping sessions.

## Methods

- Data cleaning and preprocessing using pandas
- Log transformation and StandardScaler
- K-Means clustering using Euclidean distance
- Elbow Method and Silhouette Score to evaluate k
- Cluster interpretation and purchase rate comparison

## Results

The analysis identified three browsing behavior groups:

| Cluster | Description | Purchase Rate |
|---|---|---|
| 0 | Highly Engaged Visitors | 24.22% |
| 1 | Casual Browsers | 12.23% |
| 2 | Brief Visitors | 0.44% |

## Tools

Python, pandas, NumPy, Matplotlib, and scikit-learn.

## Code

See `Online_Shopping_Clustering.ipynb` for the analysis.
