# Customer Behavior Dashboard

## 📊 Overview

This project analyzes customer purchasing behavior using **PostgreSQL, SQL and Power BI**.

The objective is to transform raw customer data into meaningful business insights through SQL analysis and an interactive Power BI dashboard.

The project focuses on **sales, revenue, customer segmentation, subscriptions, discounts, product performance and customer demographics**.

---

## 🎯 Objectives

The main objectives of this project are to:

- Analyze customer purchasing behavior
- Identify the categories and products generating the most revenue
- Compare sales across customer segments
- Analyze revenue by gender and age group
- Evaluate the impact of discounts
- Analyze customer subscription status
- Identify new, returning and loyal customers
- Analyze product ratings
- Build an interactive business dashboard

---

## 🛠️ Technologies

- **PostgreSQL** — Database management and SQL analysis
- **SQL** — Data analysis and business queries
- **Power BI** — Data visualization and dashboard creation
- **DAX** — Measures and calculations
- **Python / Pandas** — Data preparation and analysis

---

## 🗄️ Dataset

The main table used in the project is:

```text
customer
```

Key columns include:

| Column | Description |
|---|---|
| `customer_id` | Unique customer identifier |
| `gender` | Customer gender |
| `age_group` | Customer age group |
| `category` | Product category |
| `item_purchased` | Purchased product |
| `purchase_amount` | Purchase amount |
| `discount_applied` | Whether a discount was applied |
| `review_rating` | Product review rating |
| `shipping_type` | Shipping method |
| `subscription_status` | Customer subscription status |
| `previous_purchases` | Number of previous purchases |

---

## 🔎 SQL Analysis

The project includes several SQL analyses, including:

### Revenue analysis

- Total revenue by gender
- Total revenue by product category
- Total revenue by age group
- Average purchase amount by shipping type

### Customer analysis

- First 20 customers
- Customers receiving discounts and spending above the average purchase amount
- Customer segmentation
- Customers with more than five previous purchases
- Customer distribution by subscription status

### Product analysis

- Top 5 products by average rating
- Top 5 products by discount rate
- Top 3 products purchased in each category

---

## 📈 Power BI Dashboard

The Power BI dashboard provides an interactive overview of customer behavior.

### Main visualizations

- **Revenue by Category**
- **Sales by Category**
- **Revenue by Age Group**
- **Revenue by Gender**
- **Customers by Subscription Status**
- **Average Review Rating by Product**
- **Discount Rate by Product**
- **Top Products by Category**
- **Customer Segmentation**

### Example KPIs

- Total Revenue
- Total Sales
- Average Purchase Amount
- Average Review Rating
- Number of Customers

---

## 💡 Key Business Questions

The analysis aims to answer questions such as:

1. Which product categories generate the most revenue?
2. Which categories have the highest number of sales?
3. Which age groups generate the most revenue?
4. Which products have the highest average ratings?
5. Which products receive the most discounts?
6. How does customer behavior differ according to subscription status?
7. How many customers are new, returning or loyal?
8. Which products are the most purchased within each category?

---

## 📂 Project Structure

```text
customer-behavior-dashboard/
│
├── README.md
│
├── sql/
│   ├── analysis.sql
│   └── queries.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
└── data/
    └── customer.csv
```

---

## 🚀 Workflow

The project follows a typical data analysis workflow:

```text
Raw Data
   ↓
Data Preparation
   ↓
PostgreSQL
   ↓
SQL Analysis
   ↓
Power BI
   ↓
Interactive Dashboard
   ↓
Business Insights
```

---

## 📌 Skills Demonstrated

This project demonstrates practical skills in:

- SQL querying
- PostgreSQL
- Data aggregation
- Filtering and grouping
- Subqueries
- Common Table Expressions (CTEs)
- Window functions
- Customer segmentation
- KPI analysis
- Data visualization
- Power BI
- DAX
- Business Intelligence

---

## 👤 Author

**Rami Ghorbel**

Business Intelligence / Data Analytics

GitHub: [ghorbelramy](https://github.com/ghorbelramy)

LinkedIn: [Rami Ghorbel](https://www.linkedin.com/in/rami-ghorbel-3a0613290/)
