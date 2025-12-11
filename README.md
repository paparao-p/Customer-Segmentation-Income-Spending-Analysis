# Customer Segmentation – Income & Spending Analysis

This project applies K-Means clustering to group mall customers based on their annual income and spending behavior. The segmentation helps businesses understand customer types, personalize marketing strategies, and improve revenue.

## Problem Statement:

Many retail businesses struggle to understand the diverse spending behaviors of their customers, which leads to poorly targeted offers and ineffective marketing.
This project focuses on segmenting customers based on their income levels and spending patterns, enabling businesses to deliver more personalized offers and increase customer engagement.

## Objective:

- Segment customers into meaningful groups using income and spending score.
- Identify purchasing patterns within each segment.
- Support targeted marketing and better business decision-making.

## Scope:

- Exploratory Data Analysis
- Univariate • Bivariate • Multivariate Analysis
- Data Pre-processing (Encoding + Scaling)
- Elbow Method for selecting optimal clusters
- K-Means clustering model
- Cluster interpretation
- Silhouette score evaluation

## Dataset Description:

The dataset contains:
Feature | Description
------- | -----------
CustomerID | Unique customer identifier
Genre | Gender of the customer (Male/Female)
Age | Age of the customer
Annual Income (k$) | Customer's annual income in thousand dollars
Spending Score (1-100) | Behaviour score assigned by the mall based on customer spending patterns
- Only Annual Income and Spending Score were used for clustering.
- Age was used later for interpreting cluster characteristics.

## Technologies Used:

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (KMeans, StandardScaler, Silhouette Score)

## Methodology:

1. Performed complete EDA
2. Cleaned and preprocessed data
3. Selected clustering features
4. Scaled features using StandardScaler
5. Choose k = 5 using the Elbow Method
6. Trained the K-Means model
7. Assigned cluster labels to all customers
8. Evaluated clusters using Silhouette Score
9. Generated business insights from clusters

## Cluster Summary Table:

Cluster | Characteristics | Strategy
------- | --------------- | --------
0 | Older, moderate income, average spending | Maintain engagement with regular offers
1 | Young adults, high income, high spending (Premium) | Retain with exclusive benefits & loyalty programs
2 | Very young, low income, high spending (Impulsive Buyers) | Increase sales using promotional campaigns
3 | Young, high income, low spending (Budget-conscious) | Offer value deals & personalized incentives
4 | Older, low income, low spending (Low-value) | Upsell slowly through awareness campaigns


## Model Performance:

- Silhouette Score: ~0.55
(Indicates well-separated and meaningful clusters)

## Conclusion:

The K-Means clustering model successfully segmented customers into five distinct and interpretable groups using annual income and spending patterns. These segments provide valuable insights that can guide targeted marketing strategies, improve customer satisfaction, and enhance business profitability.

## Business Insights:

- Premium Customers (Cluster 1): High value; retain through exclusive benefits.

- Impulsive Buyers (Cluster 2): Increase short-term revenue with aggressive offers.

- Budget-Conscious (Cluster 3): Respond well to discounts and value packs.

- Average Customers (Cluster 0): Stable group; engage with personalized recommendations.

- Low-Value Customers (Cluster 4): Upsell gradually through awareness campaigns.

## Final Summary:

This project offers a clear understanding of purchasing behavior through customer segmentation. By identifying meaningful customer groups, businesses can personalize marketing, optimize engagement, and drive profitability through data-driven strategies.
