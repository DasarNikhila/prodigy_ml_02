# prodigy_ml_02
# 🧠 Task-02: Customer Segmentation with KMeans Clustering
This project is part of my Machine Learning Internship at *Prodigy InfoTech*.

## ✅ Objective
Segment customers into meaningful groups based on:

- *Age*
- *Annual Income*
- *Spending Score*

The goal is to identify clusters that help understand customer behavior for business decision-making.

---

## 📁 Files in this Repo
- kmeans_customer_segmentation.ipynb — Complete notebook with:
  - Data preprocessing
  - KMeans clustering with optimal K using Elbow Method
  - 2D and 3D visualization of clusters
  - Exported cluster summaries

- clustered_customers.csv — Cleaned data with cluster labels  
- cluster_profiles_summary.csv — Mean profiles for each cluster  

---

## 📊 Cluster Profiles (Sample Output)

| Cluster | Average Age | Average Annual Income (k$) | Average Spending Score |
|---------|-------------|----------------------------|------------------------|
| 0       | 50.41       | 60.47                      | 33.34                  |
| 1       | 32.85       | 87.34                      | 79.98                  |
| 2       | 25.14       | 43.27                      | 56.51                  |

### 🔍 Insights:
- *Cluster 0*: Older customers with moderate income and low spending – low engagement segment.
- *Cluster 1*: Mid-aged, high-income, high-spending – premium target segment.
- *Cluster 2*: Younger customers, average income, good spending – potential growth segment.

---

## 📌 Key Techniques Used
- 📊 KMeans Clustering (sklearn)
- 📏 Feature Scaling (StandardScaler)
- 📉 Elbow Method to determine optimal clusters
- 📌 Data visualization using matplotlib, seaborn, and mpl_toolkits for 3D plots

---

## 🛠 Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib (2D and 3D plots)
- Jupyter Notebook

---

## 📬 Connect with Me
- 🔗 [LinkedIn](https://www.linkedin.com/in/dasari-nikhila-20a0b5321/)
- 📧 [Email](nikhiladasari07@gmail.com)
