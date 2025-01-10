# MallCustomerSegmentation
This project focuses on segmenting mall customers based on purchasing behavior and demographics using unsupervised learning techniques. The dataset includes features such as annual income, spending score, and age. The goal is to categorize customers into distinct segments for targeted marketing and personalized service. 

## Overview

This project focuses on performing customer segmentation using the **Mall Customer Dataset** from Kaggle. The aim is to identify distinct customer groups based on their demographics and purchasing behavior. The resulting segments will help design targeted marketing strategies to enhance customer engagement and drive sales.

## Dataset Overview

The dataset used in this analysis, **Mall Customer Dataset**, contains various attributes related to mall customers. The key features are:

- **CustomerID**: A unique identifier for each customer.
- **Gender**: The gender of the customer (Male/Female).
- **Age**: The age of the customer.
- **Annual Income (k$)**: The customer’s annual income in thousands of dollars.
- **Spending Score (1-100)**: A score assigned by the mall, representing the customer’s behavior and spending patterns.

## Methodology

The analysis followed these steps:

1. **Data Preprocessing**: The dataset was cleaned by handling missing values and normalizing the features to prepare for clustering.
2. **Clustering Approach**: We applied the K-Means clustering algorithm to segment customers. The optimal number of clusters was determined using the Elbow Method and Silhouette Score.
3. **Cluster Profiling**: After clustering, each customer was assigned to a specific group. We analyzed the characteristics of each cluster to understand the distinct customer types.

## Key Findings

The segmentation revealed six unique customer groups:

- **Cluster 1**: Young customers with high spending scores but low income.
- **Cluster 2**: Older customers with moderate spending scores and income.
- **Cluster 3**: Middle-aged customers with low spending scores but high income.
- **Cluster 4**: Adult customers with average spending scores and moderate income.
- **Cluster 5**: Young to middle-aged customers with strong spending scores and high income.
- **Cluster 6**: Middle-aged customers with low spending scores and low income.

## Analysis of Clusters

- **High-Spending Segments**: Clusters 1 and 4 exhibit high spending behavior. Cluster 1 represents younger customers with lower income, while Cluster 4 contains higher-income customers. Tailored marketing strategies will be required for each group to address their specific needs.
- **Moderate-Spending Segments**: Clusters 2 and 3 have moderate spending scores and income. These segments can be targeted with offers that balance cost-effectiveness and perceived value.
- **Low-Spending Segments**: Clusters 5 and 6 are characterized by low spending. Cluster 5 includes wealthier individuals who are more conservative in their spending, while Cluster 6 consists of lower-income individuals with limited discretionary spending power.

## Conclusion

The segmentation analysis provides valuable insights for creating personalized marketing strategies. For instance, high-value customers in Clusters 1 and 4 could be targeted with premium offers, while moderate-spending groups (Clusters 2 and 3) might benefit from value-driven promotions. Low-spending segments (Clusters 5 and 6) could be engaged through discounts or budget-friendly campaigns.

## References

- [Mall Customer Dataset on Kaggle](https://www.kaggle.com/datasets/shwetabh123/mall-customers?resource=download)
