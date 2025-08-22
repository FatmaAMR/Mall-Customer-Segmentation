# Mall Customer Segmentation

This project applies **Unsupervised Learning (Clustering)** techniques to segment customers of a mall based on their **Annual Income** and **Spending Score**.  
The goal is to identify meaningful customer groups to support **targeted marketing strategies** and **better decision-making**.

---

## Dataset
- Source: [Mall Customer Dataset (Kaggle)](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial)
- Key features used:
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

---

## Methods Used

### 1. **K-Means Clustering**
- Applied the **Elbow Method** to determine the optimal number of clusters.  
- Segmented customers into distinct groups based on similarity in spending and income.  
- Visualized clusters in 2D space.

### 2. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
- Identified clusters based on data density.  
- Detected **outliers/noise points** that do not belong to any cluster.  
- Provided more flexibility in finding non-spherical clusters compared to K-Means.

---

## Results
- **K-Means** produced well-separated clusters and clear customer segments.  
- **DBSCAN** successfully detected natural groupings and highlighted noise (outliers).  
- Both methods provided insights into:
  - Average spending per cluster  
  - Average income per cluster  
  - Profiles of high-value vs low-value customer groups  

---

## Insights
- Clustering helps identify **premium customers**, **budget customers**, and **potential churners**.  
- Mall management can use these profiles to design **personalized offers** and **loyalty programs**.

---

## Tools & Libraries
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

