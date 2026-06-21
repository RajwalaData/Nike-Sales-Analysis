# 👟 Nike Sales Analysis Dashboard

## 📌 Project Overview

This project focuses on analyzing Nike sales data to uncover business insights, identify sales trends, and build an interactive Power BI dashboard for decision-making.

The project covers the complete Data Analytics workflow:

Raw Data → Data Cleaning → EDA → Business Insights → SQL Analysis → Power BI Dashboard

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- MySQL
- Power BI
- Excel
- Matplotlib
- Seaborn

---

## 📂 Dataset Information

The dataset contains Nike sales transactions across multiple product categories, regions, customer segments, and sales channels.

### Main Columns

- Order_ID
- Gender_Category
- Product_Category
- Product_Name
- Size
- Units_Sold
- MRP
- Discount_Applied
- Order_Date
- Sales_Channel
- Region
- Revenue

---

# 🧹 Data Cleaning

The following data cleaning tasks were performed using Pandas:

✅ Handled missing values

✅ Converted date columns to datetime format

✅ Standardized region names

✅ Fixed inconsistent text values

✅ Removed data quality issues

✅ Created Revenue column

✅ Verified data types

---

# 📊 Exploratory Data Analysis (EDA)

Analysis performed:

- Revenue Analysis
- Product Performance Analysis
- Region Analysis
- Customer Segment Analysis
- Sales Channel Analysis
- Yearly Revenue Trends
- Monthly Revenue Trends

---

# 💡 Key Business Insights

### Revenue Overview

| Metric | Value |
|----------|----------|
| Total Revenue | ₹20.8M+ |
| Average Revenue | ₹8.3K |
| Highest Revenue Order | ₹39.9K |

---

### Product Category Performance

| Product Category | Revenue |
|----------|----------|
| Lifestyle | ₹4.55M |
| Training | ₹4.45M |
| Basketball | ₹4.29M |
| Running | ₹3.86M |
| Soccer | ₹3.64M |

### Top Insight

🏆 Lifestyle generated the highest revenue.

---

### Units Sold by Category

| Product Category | Units Sold |
|----------|----------|
| Training | 958 |
| Lifestyle | 920 |
| Basketball | 890 |
| Soccer | 841 |
| Running | 806 |

### Top Insight

🏆 Training products sold the highest number of units.

---

### Revenue by Region

| Region | Revenue |
|----------|----------|
| Mumbai | ₹3.80M |
| Delhi | ₹3.65M |
| Bengaluru | ₹3.52M |
| Kolkata | ₹3.47M |
| Hyderabad | ₹3.21M |
| Pune | ₹3.16M |

### Top Insight

🌍 Mumbai contributed the highest revenue.

---

### Revenue by Customer Segment

| Segment | Revenue |
|----------|----------|
| Women | ₹7.08M |
| Men | ₹6.94M |
| Kids | ₹6.78M |

### Top Insight

👩 Women generated the highest revenue.

---

### Sales Channel Performance

| Channel | Revenue |
|----------|----------|
| Online | ₹10.54M |
| Retail | ₹10.26M |

### Top Insight

🛒 Online sales slightly outperformed retail sales.

---

### Revenue Trend

| Year | Revenue |
|----------|----------|
| 2023 | ₹1.41M |
| 2024 | ₹9.70M |
| 2025 | ₹9.69M |

### Top Insight

📈 Revenue increased significantly from 2023 to 2024 and remained stable in 2025.

---

# 🗄️ SQL Analysis

Business questions answered using MySQL:

- Total Revenue Analysis
- Product Category Analysis
- Top Selling Products
- Region Performance Analysis
- Customer Segment Analysis
- Sales Channel Analysis
- Revenue Trends
- Ranking Analysis
- Window Function Analysis

Example Query:

```sql
SELECT Product_Category,
       ROUND(SUM(Revenue),2) AS Revenue
FROM nike_sales_data
GROUP BY Product_Category
ORDER BY Revenue DESC;
```

---

# 📈 Power BI Dashboard

The dashboard includes:

### KPI Cards

- Total Revenue
- Total Orders
- Total Units Sold
- Average Revenue

### Visualizations

- Revenue Trend Analysis
- Revenue by Product Category
- Revenue by Region
- Revenue by Gender
- Revenue by Sales Channel
- Top 5 Products Analysis
- Product-Level Detail Pages

### Interactive Features

✅ Dynamic Filtering

✅ Product Navigation Pages

✅ Product-Level Analytics

✅ Interactive Slicers

---

# 🎯 Business Recommendations

1. Focus marketing efforts on Lifestyle products.
2. Increase inventory for Training products due to high demand.
3. Expand campaigns in Mumbai and Delhi.
4. Strengthen online sales channels.
5. Create targeted campaigns for women customers.


This project demonstrates:

- Data Cleaning using Pandas
- Exploratory Data Analysis
- Business Insight Generation
- SQL Analytics
- Power BI Dashboard Development
- Data Storytelling
- Business Intelligence Reporting
