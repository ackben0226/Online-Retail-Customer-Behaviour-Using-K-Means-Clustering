# 🧠 Online Retail Customer Behaviour Using K-Means Clustering

__Can Data-Driven Customer Segmentation Drive Revenue Growth?__
<br/> In today’s competitive e-commerce landscape, understanding your customers is no longer optional — it’s mission-critical. Inspired by my passion for turning data into strategy, I embarked on this project to explore how unsupervised learning can segment customers based on behavioral traits and purchasing patterns.

Through robust data analysis and K-Means clustering, I aimed to answer critical questions:

- Can customer behavior be grouped meaningfully using machine learning?

- How do we identify high-value, loyal customers vs. one-time buyers?

- What segmentation strategy leads to better targeting and retention?

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-KMeans-yellowgreen)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Objective
This project focuses on analyzing online retail customer data using RFM (Recency, Frequency, Monetary) metrics to build actionable customer segments with K-Means clustering. The goal is to enhance customer targeting, optimize marketing campaigns, and increase customer lifetime value (CLV).

## 🧰 Tools & Technologies
- Python, Pandas, NumPy
- Scikit-learn (KMeans, StandardScaler)
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🛠️ 2. Actions
**✅ Data Collection and Preparation**
Cleaned 500K+ transaction records (handled nulls, returns, duplicates)

Filtered to valid customer purchases and computed Total Revenue per transaction

**✅ Feature Engineering (RFM Analysis)**
**Recency:** Days since last purchase
**Frequency:** Total number of transactions
**Monetary:** Total amount spent

**✅ Data Transformation**
Scaled RFM values using StandardScaler for optimal clustering performance

**✅ Clustering & Optimization**
- Used **Elbow Method** and **Silhouette Score** to determine the optimal number of clusters (K = 4)
- Applied **K-Means Clustering** to segment customers
- Visualized clusters with Seaborn and Matplotlib

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
```

---

## 📂 Files
- `Online Retail Customer Behaviour Using K-Means Clustering II.ipynb`
- `kmeans_plot_1.png` – Elbow Method
- `kmeans_plot_2.png` – Cluster Visualization
- `kmeans_plot_3.png` – Heatmap
- `kmeans_plot_4.png` – Distribution Plot

---

## 📬 Connect with Me
[LinkedIn](https://www.linkedin.com/in/YOUR_PROFILE) · [Portfolio](https://YOUR_PORTFOLIO_LINK)
