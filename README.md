# 📊 E-Commerce Sales Analytics Using SQL

A complete **end-to-end SQL project** that analyses e-commerce sales performance across customers, products, categories, regions, and returns.
This project answers real business questions and demonstrates strong data analysis skills using SQL.

---

## 🗂️ **Database Schema**

The project uses 5 main tables:

* **Customers**
* **Products**
* **Orders**
* **OrderDetails**
* **Regions**
* **Returns** *(if included)*

These tables together represent a real-world e-commerce transactional system.

---

## 🎯 **Project Objectives**

This project answers 25+ business questions grouped into insights:

### **1. General Sales Insights**

* Total revenue generated
* Revenue excluding returned orders
* Revenue per year & month
* Revenue by product & category
* Average Order Value (AOV)
* AOV by year/month
* Average order size by region

### **2. Customer Insights**

* Top 10 customers by total spending
* Repeat customer rate
* Average time between orders (region-wise)
* Customer segmentation:

  * **Platinum:** >1500
  * **Gold:** 1000–1500
  * **Silver:** 500–999
  * **Bronze:** <500
* Customer Lifetime Value (CLV)

### **3. Product & Order Insights**

* Top 10 products by quantity sold
* Top 10 products by revenue
* Products with the highest return rate
* Return rate by category
* Average product price per region
* Sales trends for each category

### **4. Temporal Trends**

* Monthly sales trends (past year)
* AOV trends by month/week

### **5. Regional Insights**

* Best and worst performing regions
* Revenue contribution across regions

### **6. Return & Refund Analysis**

* Return rate by product
* Return rate by category
* Return rate by region
* Customers with frequent returns

---

## 🛠️ **Technologies & SQL Concepts Used**

* **MySQL / SQL Workbench**
* Joins (INNER, LEFT)
* Aggregations
* Window Functions
* Common Table Expressions (CTEs)
* Subqueries
* Date & time functions
* Grouping & ordering
* Data normalization

---

## 📁 **Project Structure**

```
📦 ecommerce-sql-analytics
├── sql/
│   ├── create_tables.sql
│   ├── insert_sample_data.sql
│   ├── ecommerce_sales_queries.sql
├── README.md
```

---

## 📊 **Key Insights Discovered**

✔ Revenue grows steadily month-on-month
✔ Electronics & Fashion are the top-performing categories
✔ Platinum customers contribute the highest revenue
✔ Certain regions show significantly higher AOV
✔ Some categories have higher return rates, affecting net revenue
✔ Top 10 products account for a major share of overall sales

---

## 🚀 **How to Use This Project**

1. Clone this repository
2. Run `create_tables.sql`
3. Load sample data using `insert_sample_data.sql`
4. Execute `ecommerce_sales_queries.sql` to generate insights
5. Modify or extend queries based on additional KPI needs

---

## 🧠 **Skills Demonstrated**

* Data Analysis using SQL
* Business KPI computation
* Customer & product behavioral analysis
* Revenue, AOV, CLV & segmentation modelling
* Trend & region-based analytics
* Writing clean, optimized SQL

---

## 🤝 **Contributions**

You are welcome to:

* Add more queries
* Improve sample data
* Build dashboards (Power BI / Tableau)
* Suggest new KPIs

---

## 📬 **Contact**

If you’d like a walkthrough or want to collaborate, feel free to reach out!

