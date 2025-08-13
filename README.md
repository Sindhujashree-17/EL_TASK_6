# 📊 Online Sales Analysis – PostgreSQL (Task 6)

## 📌 Overview
This project focuses on analyzing **online sales transaction data** using PostgreSQL and pgAdmin4.  
The dataset contains detailed order-level information including invoice details, product data, customer demographics, pricing, discounts, and returns.

The main goal of **Task 6** is to:
- Calculate **monthly revenue** and **order volume**.
- Identify top-performing months, categories, customers, and sales channels.
- Generate insights to support data-driven business decisions.

---

## 🗂 Dataset Information
**File Name:** `online_sales6.csv`  
**Source:** Kaggle  
**Data Type:** Transactional sales data  
**Key Columns:**
- **invoiceno** – Invoice number for each transaction
- **stockcode** – Product identifier
- **description** – Product description
- **quantity** – Number of units sold
- **invoicedate** – Date and time of the transaction
- **unitprice** – Price per unit
- **customerid** – Unique customer identifier
- **country** – Customer location
- **discount** – Discount applied to the sale
- **paymentmethod** – Payment method used
- **shippingcost** – Cost of shipping
- **category** – Product category
- **saleschannel** – Channel of sale (e.g., online, offline)
- **returnstatus** – Status indicating if the product was returned
- **shipmentprovider** – Courier used for delivery
- **warehouselocation** – Warehouse from which the product was dispatched
- **orderpriority** – Priority level of the order

---

## 🛠 Tools & Technologies
- **PostgreSQL** – Database for storing and querying data
- **pgAdmin4** – GUI tool for PostgreSQL database management
- **Kaggle Dataset** – Source of the transactional sales data
- **SQL** – Used for data aggregation, filtering, and analysis

---

## 🎯 Objectives
- Import and store the dataset into PostgreSQL.
- Perform data cleaning and type casting for accurate calculations.
- Use SQL aggregations to analyze monthly trends.
- Explore additional metrics such as:
  - Top months by revenue
  - Revenue by category
  - Customer spending patterns
  - Return rate analysis

---

## 📈 Insights Expected
- Seasonal trends in sales performance
- Best-selling product categories
- Top revenue-generating customers
- Most effective sales channels
- Potential areas for operational improvement based on return rates

