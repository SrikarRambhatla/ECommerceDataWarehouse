# Insight Sphere: E-Commerce

## Special Topics in Business Intelligence (Data Integration)

### Submitted By:
- Saisreeja Yalavarthi (yalavarthi.sa@northeastern.edu)
- Srikar Rambhatla (https://github.com/SrikarRambhatla)

---

## Problem Statement:
The rapid growth of e-commerce has been driven by expanding internet access and evolving customer preferences for online shopping. E-commerce platforms accumulate vast amounts of customer interaction data, including reviews that offer insights into product quality, customer preferences, and seasonal trends.

## Business Flow Proposed:
This project aims to develop a centralized e-commerce database integrating transactional and descriptive data. By analyzing customer orders, producers gain insights into high-demand products. Buyer reviews provide feedback to sellers for product improvements. The platform's holistic view enables trend analysis based on external factors like holidays and weather, influencing sales and order patterns.

## Data Sources:
- [UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)
- [Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data?select=olist_geolocation_dataset.csv)

---

## ETL Pipeline Implementation:

### 1. Implementation of Relational Model in PostgreSQL:
- Created table schemas in PostgreSQL.
- Utilized Python scripts for inserting normalized data into PostgreSQL.

### 2. ETL Jobs in Talend:
- Implemented ETL (Extract, Transform, Load) processes using Talend for various tables:
  - Customers
  - Orders
  - Order Delivery
  - Payments
  - Products
  - Product Details
  - Sellers
  - Reviews
  - Sales Details

### 3. Data Migration:
- Data propagated successfully to the target PostgreSQL database.

---

## KPI Metrics:
- **Total Revenue by State:** Reflects past performance; evaluates historical sales trends.
- **Line Graph Indicating Sales Over Years:** Historical sales performance visualization.
- **Number of Deliveries Made Per Quarter:** Leading indicator of future business performance.
- **Top 10 Product Categories Based on Quantity of Orders:** Real-time insights into product demand.
- **Stacked Bar Graph of Monthly Sales Payment Method vs Quantity of Orders:** Real-time sales and payment trend visualization.

---

## Dashboard:

**State-wise Overall Amount of Orders (Revenue) Generated in 2 Years:**
- Metric: Total revenue generated per state over a two-year period.

**Line Graph Indicating Sales Over Years:**
- Metric: Total sales volume over sequential years.

**Number of Deliveries Made Per Quarter:**
- Metric: Total count of deliveries completed each quarter.

**Top 10 Product Categories Based on Quantity of Orders:**
- Metric: Quantity of orders per product category, identifying top performers.

**Stacked Bar Graph of Monthly Sales Payment Method vs Quantity of Orders:**
- Metric: Quantity of orders split by payment methods across months.

---

This README provides an overview of the Insight Sphere: E-Commerce project, highlighting the integration of data sources, ETL pipeline implementation, key performance indicators (KPIs), and interactive dashboard for comprehensive business intelligence and decision-making.
