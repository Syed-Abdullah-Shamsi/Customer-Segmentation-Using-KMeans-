# Customer-Segmentation-Using-KMeans-
Customer Segmentation using K-Means Clustering, PCA Visualization, and Marketing Strategy Analysis on Mall Customers Dataset.
# Customer Segmentation Using K-Means Clustering

## Objective

The objective of this project is to segment mall customers into different groups based on their spending behavior and annual income using K-Means Clustering. These customer segments can help businesses create targeted marketing strategies and improve customer engagement.

---

## Dataset

Dataset: Mall Customers Dataset

Features:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## Project Workflow

### 1. Data Preprocessing
- Loaded dataset
- Checked missing values
- Checked duplicate records
- Encoded categorical variables

### 2. Exploratory Data Analysis (EDA)
- Gender Distribution
- Age Distribution
- Income Distribution
- Spending Score Distribution
- Correlation Analysis

### 3. Feature Scaling
StandardScaler was applied before clustering.

### 4. Elbow Method
Used to determine the optimal number of clusters.

### 5. K-Means Clustering
Customer segments were created using K-Means.

### 6. Silhouette Score
Evaluated clustering quality.

Silhouette Score:

0.4166

### 7. PCA Visualization
PCA was used to reduce dimensions and visualize customer clusters.

---

## Cluster Summary

### Cluster 0
- Older customers
- Low income
- Low spending
- Budget-conscious customers

### Cluster 1
- Young customers
- Moderate income
- High spending
- Active shoppers

### Cluster 2
- High income
- High spending
- VIP customers

### Cluster 3
- High income
- Low spending
- Potential customers

### Cluster 4
- Average income
- Average spending
- Stable customers

---

## Marketing Strategies

### Cluster 0
Discounts and affordable product promotions.

### Cluster 1
Loyalty programs and trend-based campaigns.

### Cluster 2
Premium memberships and exclusive offers.

### Cluster 3
Personalized marketing campaigns.

### Cluster 4
Retention and referral programs.

---

## Conclusion

K-Means clustering successfully identified five customer segments based on spending behavior and annual income.

The PCA visualization clearly separated customer groups, and the Silhouette Score confirmed acceptable clustering performance.

These insights can help businesses improve customer targeting and marketing efficiency.

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- PCA
- K-Means Clustering

- Author
- Syed Abdullah Shamsi 
