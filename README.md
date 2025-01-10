# Customer Segmentation Analysis using the Mall Customer Dataset

## Introduction

This project involves performing customer segmentation on the Mall Customer dataset from Kaggle to identify distinct customer groups. The primary goal is to create meaningful segments that can be targeted with personalized marketing strategies to improve customer engagement and sales.

## Data Description

The dataset used in this analysis, **Mall Customer Dataset**, contains information on customers of a mall, including the following features:

- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer (Male/Female).
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer in thousand dollars.
- **Spending Score (1-100)**: A score assigned by the mall, based on customer behavior and spending patterns.

## Methodology

The analysis was conducted using the following steps:

1. **Data Preprocessing**: The dataset was cleaned, missing values were handled, and features were normalized for clustering purposes.
2. **Clustering Algorithm**: K-Means clustering was used to segment the customers. The optimal number of clusters was determined using the Elbow Method and Silhouette Score.
3. **Cluster Analysis**: After applying the K-Means algorithm, each customer was assigned to a cluster, and the characteristics of each cluster were analyzed.

## Results

The analysis resulted in the identification of six distinct customer segments:

- **Cluster 1**: Young customers with a high spending score and low income.
- **Cluster 2**: Older customers with a medium spending score and moderate income.
- **Cluster 3**: Middle-aged Customers with a low spending score and high income.
- **Cluster 4**: Adult Customers with a average spending score and moderate income.
- **Cluster 5**: Young to Middle-aged Customers with a strong spending score and high income.
- **Cluster 6**: Middle-aged Customers with a low spending score and low income.

## Interpretation of Results

- **High Spenders Clusters**: Clusters 0 and 4 show high spending scores, but they differ significantly in age and income. Cluster 0 includes younger customers with low income, while Cluster 4 includes higher-income individuals. Different marketing strategies would be needed for each segment.
- **Moderate-Spending Clusters**: Clusters 1 and 3 have moderate spending scores and income levels. These groups could be targeted with offers that balance affordability and value.
- **Low-Spending Clusters**: Clusters 2 and 5 are low-spending groups. Cluster 2 includes wealthier individuals who choose to spend conservatively, while Cluster 5 includes lower-income individuals who may lack discretionary spending power.

## Conclusion

The customer segmentation analysis has provided actionable insights that can be used to tailor marketing strategies to different customer groups. For example, targeted campaigns could focus on high-value customers, retention strategies for Moderate-Spending customers, and discount-driven promotions for Low-Spending.

## References

- [Mall Customer Dataset on Kaggle](https://www.kaggle.com/datasets/shwetabh123/mall-customers?resource=download)