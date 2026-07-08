# SmartCart-Customer-Segmentation-and-Business-Insights

##  Project Overview

SmartCart is a fictional e-commerce platform. This project applies **unsupervised machine learning** techniques to segment customers based on their demographic and behavioral characteristics.

The objective is to identify meaningful customer groups that can help businesses improve personalized marketing, customer engagement, product recommendations, and overall business decision-making.

---

##  Objectives

- Analyze customer data to discover hidden customer segments.
- Perform data preprocessing and feature engineering.
- Reduce feature dimensions using Principal Component Analysis (PCA).
- Compare multiple clustering algorithms.
- Evaluate clustering performance using Elbow Method and Silhouette Score.
- Generate actionable business insights for each customer segment.

---

##  Dataset

The dataset contains customer demographic and lifestyle information collected from SmartCart customers.

### Features Used

- Age
- Gender
- Education
- Living With
- Income
- Spending-related attributes
- Other demographic and customer-related features

---

##  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

##  Project Workflow

### 1. Data Collection

- Loaded the customer dataset.

### 2. Data Cleaning

- Handled missing values
- Removed duplicate records
- Handled inconsistent data

### 3. Feature Engineering

- Created meaningful features from existing attributes.
- Selected relevant features for clustering.
- Removed unnecessary columns.
- Prepared the dataset for machine learning.

### 3. Exploratory Data Analysis (EDA)

- Correlation Analysis
- Distribution Analysis
- Data Visualization

### 4. Data Preprocessing

- One-Hot Encoding for categorical variables
- Feature Scaling using StandardScaler

### 5. Dimensionality Reduction

- Applied Principal Component Analysis (PCA) to reduce dimensionality while preserving maximum variance.

### 6. Clustering Algorithms

The following clustering algorithms were implemented and compared:

- K-Means Clustering
- Agglomerative Clustering 
  

### 7. Model Evaluation

The clustering models were evaluated using:

- Elbow Method
- Silhouette Score

### 8. Cluster Visualization

- PCA Scatter Plot
- 3D Cluster Visualization
- Cluster Distribution
- Feature-wise Cluster Analysis

### 9. Business Insights

Customer segments were analyzed to derive business recommendations and marketing strategies.

---

##  Results

- Successfully identified meaningful customer segments.
- Reduced high-dimensional data using PCA for better visualization.
- Compared K-Means and Hierarchical Clustering techniques.
- Evaluated cluster quality using Silhouette Score and Elbow Method.
- Generated actionable business insights to support customer-centric decision making.

---

##  Business Insights

### 🟢 Cluster 0 - Family Shoppers

- Customers are price-sensitive and prefer value-for-money purchases.
- Discounts and family bundle offers are likely to improve engagement.

### 🔵 Cluster 1 - Loyal Customers

- Customers show consistent purchasing behavior and moderate to high spending.
- Loyalty programs and personalized recommendations can improve retention.

### 🟡 Cluster 2 - Digital Browsers

- Customers are highly active online but spend relatively less.
- Sales and Heavy discounts and coupons can increase conversions

### 🔴 Cluster 3 - High-Value Customers

- This segment contributes the highest revenue and spending.
- Premium services and exclusive offers should be prioritized for these customers.


---

##  Future Improvements

- Implement Gaussian Mixture Models (GMM) and OPTICS for additional comparison.
- Develop a real-time customer segmentation pipeline.
- Integrate customer segmentation with a recommendation system.
- Perform periodic retraining as new customer data becomes available.


---


##  Machine Learning Concepts Used

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- One-Hot Encoding
- Feature Scaling
- Principal Component Analysis (PCA)
- K-Means Clustering
- Hierarchical Clustering
- DBSCAN
- Elbow Method
- Silhouette Score
- Cluster Analysis
- Data Visualization
- Business Analytics

---

##  Applications

- Customer Segmentation
- Targeted Marketing
- Customer Retention
- Personalized Product Recommendations
- Business Intelligence
- Customer Relationship Management (CRM)

---

##  Author

**Bhawna Yadav**
