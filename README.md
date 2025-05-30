# 🛍️ ShopNest Retail Analytics Dashboard - Power BI Project

A comprehensive Power BI dashboard project designed to analyze sales, customer behavior, delivery performance, product ratings, payment methods, and regional insights using a retail dataset for **ShopNest**.

### Dashboard Link : [https://drive.google.com/file/d/1DsKtOWheCl0uT3fwDACtsIPO3jGxlmdl/view?usp=sharing](https://drive.google.com/file/d/1N4Ttmpe8FUd2htyZxY7K1zw0b34NC3ZG/view?usp=sharing)

---

## 📊 Project Overview

This Power BI project answers key business questions for a retail company using advanced data modeling and visual analytics. It brings together 9 datasets and uncovers actionable insights through interactive dashboards.

---

## 🗂️ Data Sources

This project uses the following datasets:

| Dataset Name              | Description |
|--------------------------|-------------|
| **Customers**            | Customer ID, ZIP code, city, state |
| **GeoLocation**          | ZIP-level geolocation data |
| **Order Items**          | Order ID, product ID, seller ID, shipping date, price, freight |
| **Order Payments**       | Payment type, installments, payment value |
| **Order Reviews**        | Customer reviews and scores |
| **Orders**               | Order timelines, statuses |
| **Products**             | Product attributes (weight, dimensions, etc.) |
| **Sellers**              | Seller location details |
| **Product Categories**   | Product category translations |

---

## 🧠 Insights & Analysis

### 1. 📦 Top Categories by Total Sales
- **Goal:** Identify the top 10 product categories by total revenue.
- **Approach:** Used DAX to calculate total price per category.
- **Visual:** Horizontal bar chart for top 10 categories by sales.

---

### 2. ⏱️ Delayed Orders Analysis
- **Goal:** Analyze delays in order deliveries across product categories.
- **Definition:** Order is delayed if actual delivery > estimated delivery.
- **Approach:** Created a calculated column to flag delays.
- **Visual:** Clustered column chart showing delays by category.

---

### 3. 📅 Monthly Comparison of Delayed vs. On-time Orders
- **Goal:** Track monthly trends of late vs. on-time deliveries.
- **Approach:** Categorized orders per month by status using DAX.
- **Visual:** Stacked column chart + drill-through feature for deep dive.

---

### 4. 💳 Payment Method Analysis
- **Goal:** Identify the most popular payment methods.
- **Approach:** Aggregated payment types and frequencies.
- **Visual:** Donut chart for payment method share.

---

### 5. ⭐ Product Rating Analysis
- **Goal:** Determine best and worst rated products.
- **Approach:** Calculated average review score per product.
- **Visual:** Dual column chart – top 10 highest and bottom 10 lowest rated.

---

### 6. 🗺️ State-wise Sales Analysis
- **Goal:** Show which states perform best and worst in sales.
- **Approach:** Aggregated sales by customer state.
- **Visual:** Map or bar chart representing high/low performing states.

---

### 7. 📈 Seasonal Sales Patterns
- **Goal:** Investigate sales trends by quarter.
- **Approach:** Extracted quarter from order date using DAX.
- **Visual:** Line chart showing seasonal peaks across quarters.

---

### 8. 💰 Revenue Trend Analysis
- **Goal:** Analyze how revenue changes year over year.
- **Approach:** Used year from order date and summed total sales.
- **Visual:** Line or area chart with yearly revenue breakdown.

---

## 🧱 Data Modeling

All datasets are integrated using Power BI relationships based on keys like `Order_id`, `Customer_id`, `Product_id`, and `Seller_id`. Optional geolocation relationships are modeled using ZIP codes.

The model follows a star schema with:
- **Fact Tables:** Orders, Order Items, Payments
- **Dimension Tables:** Customers, Products, Categories, Sellers, Reviews

---

## 📁 Project Structure

