# 🛍️ Customer Purchase Prediction & Recommendation System
![Customer Purchase Prediction](https://github.com/user-attachments/assets/94d829cf-e55d-4c1c-beee-48f39407a918)

A full-stack Data Science project focused on analyzing customer behavior, predicting repeat purchases, and generating product recommendations using retail sales data.

## 📌 Project Overview

This project leverages a UK-based online retail dataset to:
- Analyze sales trends across countries and time
- Engineer RFM (Recency, Frequency, Monetary) features
- Predict customer repeat purchases using a Random Forest model
- Recommend similar customers using cosine similarity
- Visualize key business metrics via Power BI

## 📁 Dataset

- Source: UCI Online Retail Dataset
- Records: ~400,000 transactions
- Fields: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

## 🧠 Key Features

### 🔍 Exploratory Data Analysis
- Top countries by revenue
- Monthly sales trends

### 📊 Feature Engineering
- RFM metrics for customer segmentation

### 🤖 Machine Learning
- Random Forest Classifier to predict repeat customers
- Cosine similarity for customer-based recommendations

### 📈 Business Dashboard
- Power BI dashboard with KPIs, trends, and segment insights

## ⚙️ Tech Stack

- Python (pandas, numpy, sklearn, matplotlib, seaborn)
- Power BI
- Jupyter / VS Code
- Git & GitHub

## 📦 How to Run

1. Clone the repo
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the main script:
```bash
python customer_analytics.py
```
4. Open the Power BI dashboard with the `.pbix` file

## 🖼️ Sample Outputs

- Confusion matrix & classification report
- Similar customer recommendations
- Exported CSVs for dashboard: `rfm_data.csv`, `sales_data.csv`

## 📊 Power BI Dashboard

Includes:
- KPI cards
- Monthly & regional trends
- Repeat vs non-repeat customers
- RFM segment analysis
- Interactive slicers

## 🙋‍♂️ Author

**Harsh Dayanand Koli**  
LinkedIn: [linkedin.com/in/harsh-koli21](https://www.linkedin.com/in/harsh-koli21/)  
GitHub: [github.com/harshkoli21](https://github.com/harshkoli21)

---

## 📄 License

MIT License – feel free to use and share.
