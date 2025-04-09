# 🧠 Online Retail Customer Behaviour Using K-Means Clustering

Customer segmentation using unsupervised machine learning to uncover behavioral patterns in online retail data.

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-KMeans-yellowgreen)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Objective
To cluster customers based on their purchasing behavior using RFM (Recency, Frequency, Monetary) analysis and K-Means clustering, enabling better targeting and business strategy.

---

## 🧰 Tools & Technologies
- Python, Pandas, NumPy
- Scikit-learn (KMeans, StandardScaler)
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📊 Methodology

1. **Data Preprocessing**
   - Removed nulls, duplicates, and returns.
   - Filtered transactions with valid CustomerID.

2. **RFM Feature Engineering**
   - Recency: Days since last purchase.
   - Frequency: Number of purchases.
   - Monetary: Total amount spent.

3. **Data Scaling**
   - Standardized RFM features for clustering.

4. **Optimal K Selection**
   - Elbow Method & Silhouette Score:

   ![Elbow Method](kmeans_plot_1.png)

5. **K-Means Clustering**
   - Clustered customers into 4 segments.
   - Interpreted and visualized the results.

   ![Clusters](kmeans_plot_2.png)

---

## 🧠 Key Insights
- High-value customers identified and profiled.
- Provided a roadmap for:
  - Loyalty programs
  - Targeted marketing
  - Churn reduction

---

## 📈 Business Impact
- Personalized customer journeys
- Optimized customer lifetime value (CLV)
- Stronger marketing ROI

---

## 🚀 How to Run
```bash
1. Clone this repo
2. Open the notebook: Online Retail Customer Behaviour Using K-Means Clustering II.ipynb
3. Run all cells
