# e-commerce-powerbi-analysis
# 📊 E-Commerce Sales Analysis (Power BI)

## 📌 Project Overview
This project analyzes an e-commerce dataset to uncover insights related to sales performance, customer behavior, and payment trends. The analysis was conducted using Power BI, with a focus on data modeling, DAX calculations, and interactive visualizations.

---

## 🧩 Dataset Description
The dataset consists of three main tables:
- **Orders Dataset**: Contains order dates and customer information  
- **Order Items**: Includes product, seller, pricing, and shipping details  
- **Payment Data**: Contains payment types and transaction values  

---

## 🛠️ Data Preparation
Data cleaning and transformation were performed using Power Query. Pre-aggregated columns were removed to ensure accurate analysis. Relationships were established using the `order_id` field to create a structured data model.

---

## 📊 Dashboard Overview
![Dashboard](01_ecommerce_dashboard_overview.png)

---

## 📦 Product Purchase Analysis
![Product Analysis](02_product_purchase_frequency.png)

> A small number of products dominate purchase frequency, indicating concentrated demand.

---

## 📈 Revenue Trend Over Time
![Revenue Trend](03_revenue_trend_over_time.png)

> Revenue shows a consistent upward trend, reflecting business growth over time.

---

## 💳 Payment Value Distribution
![Payment Analysis](04_payment_value_distribution.png)

> Credit card payments account for the majority of transaction value, highlighting customer preference for flexible payment options.

---

## 🧍 Seller Performance
![Seller Analysis](05_seller_sales_performance.png)

> A few sellers contribute significantly to total sales volume, suggesting reliance on top-performing sellers.

---

## 🚚 Shipping Cost Analysis
![Shipping Analysis](06_shipping_cost_analysis.png)

> Shipping costs vary across products, which may impact pricing and profitability.

---

## ⚠️ Challenges Faced
- Handling multiple date fields and selecting the most relevant one  
- Removing pre-aggregated columns to avoid misleading results  
- Building accurate relationships between tables  

---

## 🚀 Tools Used
- Power BI  
- DAX (Data Analysis Expressions)  
- Power Query  

---

## 📌 Conclusion
This project demonstrates how data can be transformed into actionable insights using Power BI. The findings can support business decisions related to product strategy, payment optimization, and operational efficiency.
