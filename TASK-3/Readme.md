# Task 3: Customer Segmentation

## Project Overview
This task focuses on segmenting eCommerce customers using clustering techniques to uncover distinct groups based on their profiles and transaction behaviors. The segmentation helps in understanding customer patterns and enabling data-driven business strategies.

---

## Steps Performed

### Data Preparation
- Combined data from `Customers.csv` and `Transactions.csv`.
- Engineered features like total spending, transaction count, total quantity purchased, and days since signup.
- Normalized numerical data for clustering.

### Clustering
- Applied the K-Means algorithm to identify customer segments.
- Used the Elbow Method to determine the optimal number of clusters.
- Evaluated clustering using the **Davies-Bouldin Index** and **Silhouette Score**.

### Visualization
- Reduced dimensionality using PCA to plot customer segments.
- Provided a clear visual representation of clusters.

---

## Deliverables
- **Code**: Jupyter Notebook implementing clustering.
- **Output**: `Customer_Clusters.csv` with cluster assignments and PCA dimensions.
- **Visualizations**: PCA-based scatter plot for segmented groups.

---

This task demonstrates the power of clustering in customer segmentation and its potential to drive data-driven business strategies.

