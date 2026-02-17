# 📊 Customer Segmentation using RFM & K-Means  
### PT Sinar Sejahtera Mandiri (Chitose) – 2023

---

## 📌 Project Overview

This project performs customer segmentation using the **RFM (Recency, Frequency, Monetary)** framework combined with **K-Means clustering** to analyze purchasing behavior of customers in 2023.

The objective is to identify high-value customers, detect churn risk, and support data-driven marketing strategies.

---

## 📂 Dataset Information

**Source:**  
Internal transaction data of PT Sinar Sejahtera Mandiri (Chitose), 2023.

**Data Characteristics:**
- Period: January – December 2023
- Total initial records: ±21,000 transaction rows
- 1,794 unique customers identified
- 217 customers with purchase frequency > 1 used for RFM analysis
- Data format: CSV
- Data type: Secondary data (real transaction data, anonymized)
- Officially approved for research purposes

**Main Variables Used:**
- Transaction date → Recency
- Number of transactions → Frequency
- Adjusted net purchase value (NETTO_adjusted) → Monetary

Data preprocessing included:
- Data type correction
- Missing value handling
- Discount adjustment normalization

---

## 📊 Methodology

### 1️⃣ Data Preparation
- Cleaning and validation of transaction records
- Aggregation per customer

### 2️⃣ RFM Calculation
- **Recency** → Days since last transaction
- **Frequency** → Total transaction count
- **Monetary** → Total adjusted purchase value

### 3️⃣ Data Normalization
- Scaling applied before clustering

### 4️⃣ Clustering (K-Means)
- Optimal cluster number determined using evaluation metrics
- Final number of clusters: **3**
- Silhouette Score: **0.5177**

---

## 📈 Segmentation Results

Customers were segmented into **3 clusters**:

---

### 🟢 Cluster Loyal (±3%)

**Characteristics:**
- High Frequency
- High Monetary
- Low Recency (recent transactions)

**Business Meaning:**
- High-value customers
- Major revenue contributors
- Must be retained with priority strategies

---

### 🟡 Cluster Potential (±54%)

**Characteristics:**
- Moderate Frequency
- Moderate Monetary
- Good Recency

**Business Meaning:**
- Customers with growth potential
- Suitable for upselling and targeted promotions
- Can be converted into loyal customers

---

### 🔴 Cluster Passive / At-Risk (±43%)

**Characteristics:**
- High Recency (inactive)
- Low Frequency
- Low Monetary

**Business Meaning:**
- High churn risk
- Require reactivation campaigns
- Need engagement strategy

---

## 💡 Key Business Insights

- A small portion of customers (~3%) contributes significantly to revenue.
- More than 40% of customers show churn indicators.
- Customer lifecycle management strategy is essential.
- RFM segmentation enables targeted marketing rather than mass promotion.

---

## 🛠 Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## ▶️ How to Run

1. Open the notebook file in Jupyter Notebook or Google Colab.
2. Upload the dataset (not included in this repository).
3. Run all cells sequentially.

---

## ⚠️ Data Confidentiality

The dataset is confidential and cannot be publicly shared.  
All sensitive customer information has been anonymized and excluded from this repository.

---

## 🚀 Author

Final academic project focusing on applied data analytics and customer behavior segmentation using real-world transaction data.
