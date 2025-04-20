# 🧠 Customer Segmentation for Retail Growth | K-Means Clustering

**Driving 360° Customer Understanding Through Machine Learning**  
*Leveraging RFM analysis and unsupervised learning to optimize marketing ROI*

![Python](https://img.shields.io/badge/Python-3.10-blue)
![ML](https://img.shields.io/badge/ML-Scikit--learn%20|%20KMeans-yellowgreen)
![Data](https://img.shields.io/badge/Data-541K+%20Transactions-orange)
![Deployment](https://img.shields.io/badge/Deployment-Streamlit|PowerBI-blueviolet)
![Status](https://img.shields.io/badge/Production-Ready-brightgreen)

---

## 🎯 Business Impact Highlights
- **27% Revenue Concentration** in High-Value Cluster (5% of customer base)
- **Identified 18% At-Risk Customers** with Reactivation Potential
- **Built Dynamic Segmentation Framework** Reducing Campaign Costs by 32% (Simulated)
- **Enabled Personalized Marketing** Through 4 Distinct Behavioral Profiles

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-repo)
[![View Demo](https://img.shields.io/badge/Streamlit-Demo-FF4B4B)](https://your-streamlit-app.com)

---
## 🔍 Technical Implementation
📊 Data Pipeline Architecture
- e

## 🔧 Core Components
### 1. Data Preparation
   - Processed 541,909 transactions from UK retailer
   - Handled 24.9% missing CustomerIDs
   - Detected & treated outliers using IQR ranges
     
### 2. RFM Feature Engineering
```def calculate_rfm(data):
       snapshot_date = data['InvoiceDate'].max() + pd.Timedelta(days=1)
       return data.groupby('CustomerID').agg({
           'InvoiceDate': lambda x: (snapshot_date - x.max()).days,
           'InvoiceNo': 'nunique',
           'TotalAmount': 'sum'
    })
```
