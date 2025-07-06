# 🛒 Ecommerce Transactions ETL & Analysis
Designed and built a data pipeline for ecommerce transactions using PySpark and SQL in Databricks. Performed data cleaning, handled missing/invalid entries, computed revenue metrics, and created visual dashboards for top products, monthly sales, and customer insights.


## 🚀 Objective

To build a data pipeline that:
- Cleans raw ecommerce transaction data
- Handles missing values and data anomalies
- Calculates revenue, customer metrics, and product trends
- Enables SQL-based analytics and visual reporting

## 🧰 Tech Stack

- **PySpark**
- **SQL**
- **Databricks Community Edition**
- (Optional) CSV Export for Power BI/Tableau

## 📂 Dataset

Sample ecommerce dataset containing:
- Invoice numbers
- Product descriptions
- Quantity, unit price
- Timestamp of purchases
- Customer ID
- Country

Source: [Kaggle Ecommerce Dataset](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

## 🧼 Data Cleaning Steps

- Removed nulls in `CustomerID`, `InvoiceNo`, etc.
- Filtered negative prices and quantities
- Converted `InvoiceDate` to timestamp
- Derived `Total = Quantity * UnitPrice`

## 📊 Key SQL Analyses

- Top 10 most sold products
- Monthly revenue trends
- Top customers by revenue
- Revenue by country

## 📸 Visualizations

Screenshots in the `screenshots/` folder show:
- Bar chart of top products
- Line chart of monthly revenue

## 💼 What I Learned

- Writing scalable ETL code using PySpark
- Working with date-time formats and data types
- Using window functions and aggregations
- Building SQL reports inside Databricks

