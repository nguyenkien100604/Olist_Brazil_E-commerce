# Brazil E-commerce Data Analysis (Power BI)

## Project Overview

This project analyzes the Brazilian E-commerce dataset from Olist using **Power BI**.  
The goal is to uncover business insights related to **sales performance, customer behavior, product trends, and seller performance**.

The project includes:

- Data modeling using a **Star Schema**
- Data transformation
- DAX measures
- Interactive dashboards

---

# Dataset

Dataset Source

Olist Brazilian E-commerce Dataset

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

The dataset contains information about:

- Orders
- Products
- Customers
- Sellers
- Payments
- Reviews
- Geolocation

---

# Data Modeling

The dataset was modeled using a **Star Schema** to optimize analytics performance.

## Fact Tables

fact_order_items  
fact_payments  
fact_reviews  

## Dimension Tables

dim_products  
dim_seller  
dim_customer  
dim_order  
dim_date  
dim_locations  

### Data Model

![Data Model](screenshot/data_model.png)

---

# Key Metrics (DAX)

Some important measures created:

Total Revenue

---

# Dashboard Pages

The dashboard contains **4 main pages**.

---

# 1. Overview Dashboard

![Overview](screenshots/overview_dashboard.png)

Key metrics:

Total Revenue  
Total Orders  
Total Customers  
Average Order Value  
Average Review Score  

Insights:

- Revenue peaked in mid-year and declined toward the end of the year.
- São Paulo contributes the highest revenue among states.
- Credit card is the dominant payment method.

---

# 2. Customer Insights

![Customer Insights](screenshots/customer_insights.png)

Analysis:

Customer distribution by city  
Customer segmentation (Low / Medium / High / VIP)  
Monthly customer trend  
Top states by customer count  

Insights:

- São Paulo has the largest customer base.
- Most customers belong to the **Low Value segment**.
- Customer growth slowed toward the end of the year.

---

# 3. Product Performance

![Product Performance](screenshots/product_performance.png)

Analysis:

Top product categories by revenue  
Product sales distribution  
Price vs revenue relationship  

Insights:

- Health & Beauty and Watches & Gifts generate the highest revenue.
- Most products are sold in the lower price range.
- Higher price does not necessarily mean higher revenue.

---

# 4. Seller Performance

![Seller Performance](screenshots/seller_performance.png)

Analysis:

Top sellers by revenue  
Slowest sellers by delivery time  
Seller rating vs revenue  

Insights:

- A small number of sellers generate a large portion of total revenue.
- Sellers with better ratings tend to achieve higher revenue.
- Some sellers have significantly longer delivery times.

---

# Demo Video

30-second dashboard walkthrough

demo/dashboard_demo.mp4

---

# Tools Used

Power BI  
DAX  
Data Modeling  
Data Visualization  

---

# Skills Demonstrated

Data Cleaning  
Data Modeling (Star Schema)  
DAX Calculations  
Business Insight Generation  
Dashboard Design  

---

# Author

Data Analyst Portfolio Project
