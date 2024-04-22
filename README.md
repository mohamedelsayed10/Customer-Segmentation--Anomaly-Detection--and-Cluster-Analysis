# Customer Segmentation, Anomaly Detection, and Cluster Analysis

![Customer Clusters](cluster_image.png)

This project focuses on customer segmentation, anomaly detection, and cluster analysis using clustering techniques on a Credit Card Dataset. The process involves data preprocessing, applying K-means and hierarchical clustering algorithms, extracting business meanings from the clusters, and describing the clusters generated.

## Overview

The project workflow includes the following steps:

1. **Data Preprocessing**: Preparing the Credit Card Dataset for analysis, including handling missing values, scaling features, and encoding categorical variables if necessary.
2. **K-means Clustering**: Using the K-means algorithm from scikit-learn to segment customers based on their credit card usage patterns.
3. **Hierarchical Clustering**: Applying hierarchical clustering from scipy to identify hierarchical relationships among customers.
4. **Business Meaning and Cluster Description**: Interpreting the clusters obtained from both K-means and hierarchical clustering to derive actionable insights for the business.

## Tools Used

- **scikit-learn**: For implementing the K-means clustering algorithm.
- **scipy**: For hierarchical clustering.
- **Pandas**: For data manipulation and preprocessing.

## General Description of Customer Clusters:

### Cluster 0: Moderate Spenders
- Customers in this cluster have a moderate balance and make moderate purchases.
- They tend to make purchases at a moderate frequency, with a mix of installment and one-off purchases.
- Overall, they exhibit average spending behavior compared to other clusters.

### Cluster 1: High Spenders with One-Off Purchases
- These customers have a relatively higher balance and make higher purchases compared to other clusters.
- They prefer one-off purchases over installment purchases.
- While they make purchases at a moderate frequency, their focus seems to be on larger one-off purchases.

### Cluster 2: High Spenders with Balanced Purchases
- Customers in this cluster have a higher balance and are high spenders.
- They make a significant portion of both one-off and installment purchases.
- They make purchases more frequently compared to other clusters and engage in a diverse range of purchase transactions.

### Cluster 3: Inactive Customers
- These customers have the highest balance but exhibit extremely low purchase activity.
- They rarely make any purchases, and when they do, it's mostly installment purchases.
- Their purchasing behavior indicates a lack of engagement with the provided services or products.

## Acknowledgements

- The project was inspired by the need to understand customer behavior and identify potential anomalies in credit card usage.
- Thanks to the developers of scikit-learn, scipy, and Pandas for their valuable tools and resources.

