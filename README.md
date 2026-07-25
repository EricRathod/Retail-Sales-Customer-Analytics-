# 📊 Retail Sales & Customer Analytics

An end-to-end **Business Data Analytics portfolio project** that analyzes retail sales, profitability, product performance, regional performance, and customer behavior using **Python, SQL, SQLite, and Power BI**.

The project transforms retail transaction data into business insights through data cleaning, KPI analysis, customer segmentation, visualization, database integration, and an interactive Power BI dashboard.

---

## 📌 Project Overview

This project analyzes **5,000 retail sales transactions** across multiple product categories, customer segments, and Canadian regions.

The objective is to answer important business questions such as:

- How much revenue and profit did the business generate?
- Which product categories generate the most revenue?
- Which products perform best?
- How does revenue change over time?
- Which regions generate the most revenue?
- Who are the most valuable customers?
- How can customers be segmented based on their purchasing value?

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- SQL
- SQLite
- Power BI
- Google Colab

---

## 📊 Power BI Dashboard

The Power BI dashboard provides an interactive overview of retail performance, including revenue, profit, orders, average order value, product performance, regional sales, customer segmentation, and transaction-level information.

![Retail Sales & Customer Analytics Dashboard](Screenshot%202026-07-22%20071043(2).png)

### Dashboard Components

**KPI Cards**

- Total Revenue
- Total Profit
- Total Orders
- Average Order Value
- Profit Margin

**Visualizations**

- Monthly Revenue Trend
- Revenue by Product Category
- Revenue by Region
- Top Products by Revenue
- Customer Value Segments
- Sales Transactions Table

---

## 📈 Key Business KPIs

| KPI | Result |
|---|---:|
| Total Revenue | $6.33M |
| Total Profit | $1.98M |
| Total Orders | 5,000 |
| Total Customers | 990 |
| Average Order Value | $1,266.76 |
| Profit Margin | 31.30% |

These KPIs provide a high-level overview of the financial and operational performance of the retail business.

---

## 📅 Monthly Revenue Analysis

Monthly sales were aggregated to identify changes in revenue, profit, order volume, customer activity, and average order value over time.

![Monthly Revenue Trend](monthly_revenue_trend(3).png)

The analysis shows noticeable month-to-month variation in revenue, with several strong revenue periods across the three-year dataset.

---

## 🛍️ Product Category Performance

Revenue and profitability were analyzed across four major product categories:

- Electronics
- Furniture
- Clothing
- Office Supplies

![Revenue by Product Category](revenue_by_category(3).png)

### Key Finding

**Electronics** is the strongest category, generating approximately **$4.20M in revenue**, substantially higher than the other categories.

Furniture generated approximately **$1.53M**, making it the second-largest revenue category.

---

## 🏆 Top Products by Revenue

Product-level analysis was performed to identify the products contributing the most revenue.

![Top 10 Products by Revenue](top_10_products(3).png)

Products such as **Keyboard, Mouse, Headphones, Laptop, and Monitor** appear among the strongest revenue-generating products in the dataset.

This analysis can help businesses prioritize inventory, marketing, and product strategies.

---

## 👥 Customer Value Segmentation

Customers were segmented into four groups based on their total revenue contribution:

- Low Value
- Medium Value
- High Value
- VIP

![Customer Value Segments](customer_segments(3).png)

The segmentation allows the business to distinguish between lower-value customers and customers who contribute significantly more revenue.

### Customer Segment Insights

| Segment | Customers | Revenue | Average Orders |
|---|---:|---:|---:|
| Low Value | 248 | $396.8K | 3.24 |
| Medium Value | 247 | $1.03M | 4.67 |
| High Value | 247 | $1.74M | 5.50 |
| VIP | 248 | $3.17M | 6.79 |

Although the number of customers is approximately evenly distributed between the four groups, the **VIP segment contributes substantially more revenue**.

This demonstrates why customer value segmentation can be useful for loyalty programs, retention campaigns, and targeted marketing.

---

## 🌎 Regional Analysis

Sales performance was also analyzed across five Canadian regions:

| Region | Revenue |
|---|---:|
| Manitoba | $1.40M |
| British Columbia | $1.29M |
| Quebec | $1.28M |
| Ontario | $1.22M |
| Alberta | $1.15M |

**Manitoba** generated the highest revenue in the dataset, while revenue remained relatively balanced across the five regions.

---

## 🗄️ SQLite Database

The processed analytics data was also exported to a SQLite database:

`retail_sales_analytics.db`

The database contains the following tables:

- `sales_transactions`
- `business_kpis`
- `monthly_sales`
- `category_summary`
- `product_summary`
- `region_summary`
- `customer_summary`
- `customer_segment_summary`

This makes the project suitable for both Python-based analysis and SQL-based exploration.

---

## 🔄 Project Workflow

```text
Retail Sales Data
        ↓
Data Cleaning & Preparation
        ↓
Exploratory Data Analysis
        ↓
Business KPI Calculation
        ↓
Product & Regional Analysis
        ↓
Customer Analytics
        ↓
Customer Value Segmentation
        ↓
SQLite Database
        ↓
Power BI Dashboard
        ↓
Business Insights
```

---

## 📂 Repository Structure

```text
Retail-Sales-Customer-Analytics/
│
├── retail_sales_data(3).csv
├── retail_kpis(3).csv
├── monthly_sales(3).csv
├── category_summary(4).csv
├── product_summary(3).csv
├── region_summary(3).csv
├── customer_summary(3).csv
├── customer_segment_summary(3).csv
│
├── retail_sales_analytics(3).db
├── dashboard(2).pbix
│
├── Eric_Rathod_Project2_Retail_Sales_Customer_Analytics.ipynb - Colab(3).pdf
│
├── Screenshot 2026-07-22 071043(2).png
├── monthly_revenue_trend(3).png
├── revenue_by_category(3).png
├── top_10_products(3).png
├── customer_segments(3).png
│
└── README.md
```

---

## 💡 Key Business Insights

1. **Electronics dominates revenue**, contributing approximately $4.20M of total sales.

2. The business generated approximately **$6.33M in total revenue** and **$1.98M in profit**.

3. The overall profit margin is approximately **31.3%**.

4. The **VIP customer segment generates approximately $3.17M**, representing a major share of overall revenue.

5. Higher-value customer segments also demonstrate greater average purchase frequency.

6. Regional revenue is relatively balanced, with **Manitoba producing the highest total revenue**.

7. Product-level analysis identifies several electronics products among the strongest revenue contributors.

---

## 🎯 Business Applications

The insights from this project could support:

- Customer retention strategies
- VIP customer targeting
- Product inventory planning
- Regional sales strategy
- Marketing campaign targeting
- Revenue monitoring
- Profitability analysis
- Business performance reporting

---

## 📚 Skills Demonstrated

- Data Cleaning
- Data Analysis
- Exploratory Data Analysis
- Business Intelligence
- KPI Development
- Customer Segmentation
- Data Visualization
- SQL & Database Management
- Power BI Dashboard Development
- Business Insight Generation
- Python Programming
- Pandas Data Analysis

---

## 👤 Author

**Eric Rathod**

Master's in Artificial Intelligence Student  
Seneca Polytechnic

Interested in **Artificial Intelligence, Machine Learning, Data Analytics, Business Intelligence, and Data Science**.

---

## ⭐ About This Project

This project was developed as part of a business data analytics portfolio to demonstrate an end-to-end analytics workflow combining **Python-based data processing, SQL/SQLite data storage, customer analytics, and Power BI business intelligence reporting**.
