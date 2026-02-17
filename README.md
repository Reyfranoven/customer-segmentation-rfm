# 📊 Customer Segmentation using RFM & K-Means

## 📌 Project Overview
This project performs customer segmentation using the RFM (Recency, Frequency, Monetary) framework combined with K-Means clustering.

The goal is to group customers based on purchasing behavior and generate actionable insights to support marketing strategy and customer retention.

---

## 📊 Methodology

### 1️⃣ Data Preparation
- Data cleaning
- Handling missing values
- Transaction aggregation per customer

### 2️⃣ RFM Analysis
- **Recency** → Days since last transaction
- **Frequency** → Total number of transactions
- **Monetary** → Total spending amount

### 3️⃣ RFM Scoring
Each customer was scored and transformed into numerical features for clustering.

### 4️⃣ Clustering (K-Means)
- Data normalization applied
- Optimal number of clusters determined using Elbow Method
- K-Means used to segment customers

---

## 📈 Segmentation Results

Customers were successfully segmented into distinct behavioral groups based on RFM characteristics.

Identified customer profiles include:

- 🟢 High-Value Customers  
  High frequency and high monetary value. Strong retention targets.

- 🟡 Potential Loyal Customers  
  Recently active with moderate spending. Good upselling opportunity.

- 🔴 At-Risk Customers  
  Low recency score and declining frequency. Require re-engagement strategy.

- ⚪ Low Engagement Customers  
  Low transaction frequency and low spending.

Each cluster demonstrates clear behavioral differences that can be used for targeted marketing campaigns.

---

## 💡 Business Insights

- High-value customers contribute significantly to total revenue.
- Certain segments show churn risk indicators.
- Personalized marketing can be implemented based on segment characteristics.
- Customer lifecycle strategy can be optimized using segmentation output.

---

## 🛠 Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 📂 Dataset

The dataset used in this project is confidential and cannot be publicly shared.  
This repository contains only the analysis workflow and modeling approach.

---

## ▶️ How to Run

1. Open the notebook file in Jupyter Notebook or Google Colab.
2. Upload the dataset (not included in this repository).
3. Run all cells sequentially.

---

## 📁 Project Structure

```
custo
