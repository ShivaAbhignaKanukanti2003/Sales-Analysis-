# Comprehensive Sales Data Analysis & RFM Segmentation 🛒📈

A complete sales data analysis project using Python, Pandas, and customer segmentation techniques.  
This repository explores EDA (Exploratory Data Analysis), RFM (Recency, Frequency, Monetary) segmentation, and insights for business decision-making based on retail sales data.

---

## 🚀 Project Summary

This analysis takes a real-world sales dataset and performs:

✔ Data cleaning and preprocessing  
✔ Exploratory Data Analysis (visual patterns + trends)  
✔ Customer segmentation using RFM  
✔ Clustering analysis for actionable customer groups  
✔ Business insights with visualizations

The goal is to **understand customer behavior** and **segment customers** for targeted marketing and improved revenue.

---

## 📊 Dataset

**Sales Data Sample** — contains transactional records including:

| Feature | Description |
|---------|-------------|
| InvoiceNo | Order invoice number |
| StockCode | Product code |
| Description | Product description |
| Quantity | Number of items purchased |
| InvoiceDate | Timestamp of transaction |
| UnitPrice | Product price |
| CustomerID | Unique customer identifier |
| Country | Country of purchase |

The dataset represents common retail sales data, suitable for customer segmentation tasks.

---

## 🧠 Steps in This Analysis

### 1. **Data Preprocessing**
- Load and inspect data
- Handle missing values
- Convert date columns to datetime
- Clean text where necessary

---

### 2. **Exploratory Data Analysis (EDA)**
Visualize and interpret:
- Sales trends over time
- Top selling products
- Customer country distribution
- Quantity and revenue distribution

Charts include:
- Line charts
- Bar plots
- Histograms
- Box plots

---

### 3. **RFM Segmentation**
RFM stands for:
- **Recency**: How recently a customer made a purchase
- **Frequency**: How often they purchase
- **Monetary**: How much revenue they generated

Customers are scored based on:
- RFM quartiles
- Combined RFM scores
- Segmented into groups such as:
  - Champions
  - Loyal Customers
  - At-Risk Customers
  - Lost Customers

This allows targeted marketing and retention strategies.

---

### 4. **Clustering**
- Scaled RFM features used for clustering
- Elbow Method to find optimal number of clusters
- KMeans clustering applied for segmentation
- Identified actionable customer groups

---

## 📈 Insights & Business Value

This analysis reveals:

- High-value customers with frequent purchases and high monetary value
- Customer groups that may need engagement (e.g., at-risk or lost)
- Seasonal or monthly sales patterns
- Product categories with highest revenue contribution

These insights help stakeholders:
- Prioritize marketing spend
- Personalize retention campaigns
- Forecast customer lifetime value
- Improve product recommendations

---

## 🛠 Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter / Kaggle Notebooks



