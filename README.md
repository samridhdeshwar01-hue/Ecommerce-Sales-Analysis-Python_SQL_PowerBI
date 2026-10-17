# 🛒 Ecommerce Sales Analysis

An end-to-end data analytics project that turns a messy raw ecommerce dataset of 113,000+ orders into an interactive Power BI dashboard for tracking sales, profit, orders and delivery performance.

![Dasboard Preview](https://github.com/samridhdeshwar01-hue/Ecommerce-Sales-Analysis/blob/main/Screenshot%20of%20Dashboard.png).

---

## 🎯 Business Problem

An ecommerce business needs to know where its sales and profit come from and where it loses orders. This project answers questions such as:

- What are the total sales, profit and orders, and how have they changed over time?
- Which products and categories drive the most sales and profit?
- Which cities generate the most orders?
- Which payment modes are customers using most?
- How many orders are cancelled, and how is delivery performing?

---

## 📝 Description

This project takes a messy raw ecommerce dataset of over 113,000 orders and turns it into clear business insights. I cleaned the data with Python (pandas and numpy) by removing duplicates, handling missing values, fixing formats and filtering invalid records, then created new metrics such as sales, net amount and profit. The cleaned data was stored in MySQL and explored with SQL to answer questions on sales, top products and cities, payment modes and cancellations. Finally, I built an interactive Power BI dashboard to track sales, orders, categories and delivery performance.

---

## 🔄 Project Workflow

```
Raw CSV → Python / Jupyter (cleaning) → MySQL (storage + SQL analysis) → Power Query → Power BI (dashboard)
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| 🐍 **Python (pandas, numpy)** | Cleaned the raw data and created new metrics such as sales, net amount and profit |
| 📓 **Jupyter Notebook** | Documented the cleaning workflow step by step |
| 🔌 **SQLAlchemy and PyMySQL** | Connected Python to MySQL and loaded the cleaned data |
| 🗄️ **MySQL and MySQL Workbench** | Stored the cleaned orders data and ran SQL queries on sales, products, cities, payment modes and cancellations |
| 📂 **Power Query** | Loaded the MySQL data into Power BI |
| 📊 **Power BI Desktop** | Built the interactive dashboard |
| 🧠 **DAX** | Calculated measures such as Total Sales, Total Profit and Total Orders |

---

## 📊 Dashboard Highlights

**KPIs:** Total Sales | Total Profit | Total Orders | *(add any others you show, for example cancellation rate or average delivery time)*

**Visuals:** Top N products by profit, monthly sales trend, sales by category, orders by city, payment mode split and delivery performance, with slicers for filtering.

---

## 🔍 Key Insights

> Replace the brackets with your real numbers from the dashboard and SQL results.

- **Total sales reached [value]** across [113,000+] orders, with a total profit of **[value]**.
- **[Top category]** is the biggest driver of sales, contributing [x]% of the total.
- **[Top city]** places the most orders, followed by [city] and [city].
- **[Payment mode]** is the most popular way to pay, used for [x]% of orders.
- **[x]% of orders were cancelled**, which is the main area of lost revenue.
- **Sales peak in [month]**, so stock and marketing can be planned around it.

---

## 💡 Recommendations

1. Put more stock and promotion behind the top-profit products and categories.
2. Focus delivery and marketing efforts on the highest-order cities.
3. Investigate the reasons behind cancellations and fix the most common ones.
4. Offer incentives on the most-used payment mode to encourage repeat purchases.

---

## 📁 Repository Structure

```
├── Raw_Ecommerce_Data.csv          # Raw dataset
├── Ecommerce_Cleaning.ipynb        # Python cleaning notebook
├── Clean_Ecommerce.csv             # Cleaned dataset
├── Ecommerce_Queries.sql           # SQL analysis queries
├── Ecommerce_Dashboard.pbix        # Power BI dashboard
├── Dashboard_Screenshot.png        # Dashboard preview
└── README.md
```
