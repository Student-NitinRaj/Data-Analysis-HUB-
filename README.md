# Data-Analysis-HUB-
# 🚗 BYD Sales Dashboard – Nepali EV Market (2021–2024)

📊 *A comprehensive data analysis and interactive visualization project on BYD electric vehicle sales trends in Nepal from 2021 to 2024.*

---

## 📌 Project Overview

This repository showcases a complete data analysis and visualization project focused on BYD's electric vehicle (EV) performance in the Nepali market from **2021 to 2024**. It includes:
DataSet:- https://github.com/Student-NitinRaj/Data-Analysis-HUB-/blob/main/BYD_Sales.csv
- In-depth **exploratory data analysis (EDA)** using Python.
- An **interactive Power BI dashboard** for key insights.
- Cleaned and raw datasets for transparency and reproducibility.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `EDA.ipynb` | Jupyter Notebook with full exploratory data analysis, visual insights, and key metrics. |
| `byd_dashboard.pbix` | Power BI file for an interactive sales dashboard. |
| `Screenshot.png` | A preview of the Power BI dashboard UI. |
| `cleaned_data.csv` | Final cleaned dataset used in analysis and dashboard. |
| `uncleaned_data.csv` | Original raw data collected for the project. |

---

## 📈 Dashboard Highlights

The **Power BI Dashboard** provides a real-time, interactive view of: 
https://github.com/Student-NitinRaj/Data-Analysis-HUB-/blob/main/Screenshot%202025-06-09%20183005.png
- 💰 **Total Revenue & Profit Overview**
- 🚘 **Top-Selling Vehicle Models & Total Units Sold**
- 🌍 **Sales Distribution by Location & Model**
- 📅 **Monthly Sales Trend Analysis**
- 🚗 **Vehicle Type Distribution**
- 💳 **Preferred Payment Methods**

> ⚡ *Built for business analysts, marketing teams, and automotive strategists to gain fast insights.*

---

## 🔧 How to Use

1. Open `EDA.ipynb` in Jupyter Notebook to explore the Python-based data analysis.
2. Launch `byd_dashboard.pbix` in **Power BI Desktop** for interactive visualization.
3. Use `cleaned_data.csv` for refined analysis and modeling.
4. Refer to `uncleaned_data.csv` to track data preprocessing steps.

---

## 🧰 Requirements

- **Jupyter Notebook** (Python 3.x)
  - Libraries: `pandas`, `matplotlib`, `seaborn`, etc.
- **Power BI Desktop** [(latest version)
](https://app.powerbi.com/groups/me/reports/f7aeca93-56cc-41a0-84ff-69e18bda5455/77015693df166f555cba?experience=power-bi)
---

## 🚀 Future Enhancements

- 📊 Integrate **predictive analytics** (e.g., sales forecasting using ML models).
- 🌐 Embed Power BI Dashboard in a **web application**.
- 🧭 Add customer demographics and satisfaction data for richer insights.
- 🛠 Include **automated data refresh** with scheduled updates in Power BI Service.

---

## 📃 License

This project is open-source. You are free to use, modify, or build upon it for educational, personal, or commercial purposes.

---

9.) Project Microsoft Powerbi link:- https://app.powerbi.com/groups/me/reports/760e8314-811a-4545-a0ca-b14f5677d466/aac64ab21b897185cb20?experience=power-bi
# 🛒 Customer Purchasing Behaviour Analysis

End-to-end data analytics project built using Python, PostgreSQL, SQL, Power BI, and Excel to solve real business problems and deliver actionable insights.

---

📌 Project Summary

This project analyzes customer purchasing behaviour for a retail business to understand buying patterns, product performance, customer loyalty, and revenue drivers.

The complete workflow follows an industry-standard analytics pipeline used in real companies — from raw data to executive-level dashboard reporting.

---

🔄 End-to-End Analytics Process

```
Business Problem Definition
        ↓
Data Cleaning & EDA (Python)
        ↓
Data Modelling & Feature Engineering
        ↓
Load Data into PostgreSQL
        ↓
SQL-Based Business Analysis
        ↓
Interactive Dashboard (Power BI)
        ↓
Business Insights & Report
        ↓
Presentation (Gamma AI)
        ↓
GitHub Portfolio Deployment
```

---

🏢 Business Objective

The company wanted to:

• Understand customer purchasing behaviour  
• Identify high-value customers  
• Measure subscription effectiveness  
• Analyze discount dependency  
• Evaluate product and category performance  
• Improve retention and marketing strategy  

---

📊 Dataset Information

• Records: 3,900 transactions  
• Features: 18 columns  
• Source: Excel retail dataset  

Key attributes include customer demographics, purchase details, discounts, shipping type, ratings, and subscription status.

---

🧹 Data Preparation (Python)

• Imported Excel data using Pandas  
• Cleaned missing review ratings  
• Standardized column naming  
• Created age-group buckets  
• Engineered customer segments  
• Removed redundant features  
• Prepared analytics-ready dataset  

---

🗄️ Database Layer

• PostgreSQL used as analytical database  
• Python connected using SQLAlchemy  
• Clean data loaded into relational tables  
• SQL queries executed on production-style schema  

---

🧮 SQL Analysis

Core SQL techniques applied:

• CTEs  
• Window functions  
• CASE statements  
• Subqueries  
• Aggregations  
• Ranking logic  

Business analysis performed:

• Revenue by gender  
• High-spending discount users  
• Top-rated products  
• Discount-dependent items  
• Subscriber vs non-subscriber analysis  
• Shipping type comparison  
• Customer segmentation  
• Top 3 products per category  
• Repeat buyers vs subscription behavior  
• Revenue contribution by age group  

---

📈 Power BI Dashboard

Interactive dashboard connected directly to PostgreSQL.

Key metrics displayed:

• Total customers  
• Average purchase amount  
• Average review rating  

Dashboard insights:

• Sales by category  
• Revenue by category  
• Subscription distribution  
• Revenue by age group  
• Sales by age group  

Interactive filters:

• Gender  
• Category  
• Subscription status  
• Shipping type  

---

🔍 Key Insights

• Non-subscribers generate higher revenue volume  
• Subscribers show stronger repeat purchasing behavior  
• Footwear and clothing drive the majority of sales  
• Middle-aged and young adult customers contribute the most revenue  
• Discounts increase volume but impact profitability  
• Frequent buyers show higher subscription likelihood  

---

💡 Business Recommendations

• Strengthen subscription benefit strategy  
• Introduce loyalty programs for repeat buyers  
• Optimize discount policies to protect margins  
• Focus campaigns on high-revenue age groups  
• Promote top-rated and best-selling products  
• Upsell express shipping to premium customers  

---

🧰 Tools Used

• Excel — raw data source  
• Python — data cleaning and EDA  
• Pandas — feature engineering  
• PostgreSQL — analytical database  
• SQL — business analysis  
• Power BI — dashboard and visualization  
• Gamma AI — business presentation  
• GitHub — project version control  

---

📁 Repository Structure

```
customer-purchasing-behaviour-analysis/
│
├── data/
│   └── customer_behavior.xlsx
│
├── python/
│   └── data_cleaning_eda.ipynb
│
├── sql/
│   └── business_queries.sql
│
├── powerbi/
│   └── customer_dashboard.pbix
│
├── presentation/
│   └── project_report.pdf
│
├── images/
│   └── dashboard_preview.png
│
└── README.md
```

---

⭐ Project Highlights

• Complete end-to-end analytics workflow  
• Real SQL business problem solving  
• PostgreSQL integration with Python  
• Professional Power BI dashboard  
• Strong business storytelling  
• Portfolio-ready industry project  

---

Skills:  
SQL • PostgreSQL • Power BI • Python • Excel • Data Analytics

---

👤 Author

**Nitin Raj**  
*Data Analyst | Power BI Enthusiast | EV Market Researcher*  
📧 nitinraj3152005@gmail.com  
🌐 https://www.linkedin.com/in/nitin-raj-102b2b2a2/
