<img width="1366" height="749" alt="dashboard_preview" src="https://github.com/user-attachments/assets/18ce62ef-f564-4929-aa60-cc9fd5a84bb3" />
# 🛍️ Customer Shopping Behavior Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python) ![SQL](https://img.shields.io/badge/SQL-Server-CC2927?logo=microsoftsqlserver) ![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi) ![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter) ![License](https://img.shields.io/badge/License-MIT-green)

**Author:** Srivani Busavaly
**Contact:** busavalysrivani@gmail.com | [LinkedIn](https://linkedin.com/in/srivanibusavaly)

---

## 📌 Project Overview

An end-to-end data analysis project examining customer shopping behavior across 3,900 customers to uncover purchasing patterns, spending habits, and business growth opportunities.

**Full pipeline:** Data Cleaning → EDA → SQL Analysis → Power BI Dashboard → Business Report → Presentation

---

## 📊 Dashboard Preview

![Customer Behavior Dashboard](dashboard_preview.png)

> *Interactive Power BI dashboard with subscription filters, gender/category slicers, revenue by age group, and category-wise sales analysis.*

---

## 🔑 Key Findings

| Metric | Value |
|---|---|
| Total Customers | 3,900 |
| Average Purchase Amount | $59.76 |
| Average Review Rating | 3.75 / 5 |
| Subscribed Customers | 27% (1,053) |
| Non-Subscribed Customers | 73% (2,847) |
| Top Revenue Category | Clothing (~$100K) |
| Top Customer Segment | Young Adults (~$60K revenue) |

**Business Insights:**
- 🏆 **Clothing dominates** revenue (~$100K) and sales volume (~1,700 units) — nearly **2× Accessories**, the second-highest category
- 👥 **Young Adults are the #1 segment**, leading both revenue (~$60K) and purchase volume (~1,000 units) across all age groups
- 📉 **73% of customers are unsubscribed** — a significant retention and loyalty program opportunity; subscribed users show higher engagement
- 🧑‍🦳 **Middle-aged customers** rank second in both revenue and sales, showing strong cross-demographic demand
- 🧥 **Outerwear underperforms** across both revenue and units sold — likely seasonal demand or a pricing/visibility issue worth investigating

---

## 🗂️ Dataset

| Column | Description |
|---|---|
| Customer ID | Unique identifier |
| Age / Gender | Demographics |
| Category | Product category (Clothing, Accessories, Footwear, Outerwear) |
| Purchase Amount | Transaction value in USD |
| Payment Method | Card, PayPal, Cash, etc. |
| Shipping Type | Standard, Express, 2-Day, Next Day Air, etc. |
| Subscription Status | Yes / No |
| Frequency of Purchases | How often the customer shops |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python (Pandas, NumPy) | Data loading, cleaning, transformation |
| Matplotlib & Seaborn | EDA visualizations |
| SQL Server | Business queries & aggregations |
| Power BI | Interactive dashboard |
| Jupyter Notebook | Analysis environment |
| Gamma | Presentation design |

---

## 📁 Project Files

| File | Description |
|---|---|
| `Customer_Shopping.ipynb` | Python EDA notebook |
| `Customer_Behavior_Analysis.sql` | SQL queries for business analysis |
| `Customer_Behavior_Dashboard.pbix` | Power BI dashboard file |
| `Customer Shopping Behavior Analysis.pdf` | Business report |
| `Customer-Shopping-Behavior-Analysis.pptx` | Presentation deck |
| `customer_shopping_behavior.csv.csv` | Dataset |

---

## ▶️ How to Run

**Python / EDA**
```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook Customer_Shopping.ipynb
```

**SQL Analysis**
- Import the CSV into SQL Server
- Run `Customer_Behavior_Analysis.sql`

**Power BI Dashboard**
- Open `Customer_Behavior_Dashboard.pbix` in Power BI Desktop

---

## 📝 Conclusion

This project demonstrates a complete data analyst workflow — from raw data to business insights. Key competencies showcased: data cleaning, exploratory analysis, SQL querying, dashboard development, and stakeholder-ready reporting.

---
*⭐ If you find this project useful, please give it a star!*
