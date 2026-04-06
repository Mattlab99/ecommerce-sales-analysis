# E-commerce Sales Performance & Operations Analysis

## Overview
This project presents an end-to-end e-commerce analytics workflow using SQL, Python, and Power BI.

The goal is to transform raw transactional data into actionable insights to support business decision-making across revenue performance, customer behaviour, and delivery operations.

---

## Tools & Technologies
- SQL (SQLite)
- Python (Pandas)
- Power BI

---

## Dataset
This project uses the Olist Brazilian E-commerce dataset:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

## Key Business Metrics

- **Total Revenue:** $15.42M  
- **Total Orders:** 96K  
- **Active Customers:** 93K  
- **Average Order Value (AOV):** $159.85  

---

## Dashboard Overview

### 1. Sales Performance

<img width="1442" height="807" alt="Overview" src="https://github.com/user-attachments/assets/23dfa8a9-7279-4dd7-801c-526c9c97c787" />


This page provides a high-level view of business performance over time.

#### Key Insights:
- Revenue shows a strong upward trend over time, peaking around late 2017–early 2018  
- Growth is primarily driven by **increase in order volume**, not AOV  
- AOV remains relatively stable, indicating consistent customer spending behaviour  
- Customer base grows steadily alongside revenue, showing healthy acquisition  

---

### 2. Category Analysis


<img width="1440" height="808" alt="Category Performance" src="https://github.com/user-attachments/assets/e52972ef-bab3-40d2-9c4f-13188d0ec8bd" />

This page explores revenue and order distribution across product categories.

#### Key Insights:
- **Health & Beauty** and **Watches & Gifts** generate the highest revenue (~$1.2M each)  
- **Bed Bath Table** leads in order volume (~11K orders), showing strong demand  
- Some categories have **high volume but lower revenue**, indicating lower-priced products  
- Revenue is concentrated in a small number of categories → potential dependency risk  

---

### 3. Delivery & Seller Performance

<img width="1442" height="807" alt="Delivery and seller info" src="https://github.com/user-attachments/assets/72454c26-141e-418f-b5a3-9d86b4873c33" />


This page evaluates operational efficiency and seller performance.

#### Key Metrics:
- **Average Delivery Time:** 12.5 days  
- **On-Time Delivery Rate:** 92%  
- **Maximum Delivery Time:** 210 days  

#### Key Insights:
- Overall delivery performance is acceptable, with high on-time rate  
- Significant variation exists between sellers → some sellers are major bottlenecks  
- Certain sellers show extremely high delivery times (100+ days), impacting customer experience  
- Delivery performance varies by customer location, suggesting geographic/logistics inefficiencies
- Delivery estimates should be more precise and well estimated

---

## Project Structure

- SQL queries → /sql  
- Python analysis → /python  
- Power BI dashboard → /powerbi  
- Dashboard images → /images  
- Dataset information → /data  

---

## Key Skills Demonstrated

- Data extraction and transformation using SQL  
- Data cleaning and analysis using Python (Pandas)  
- KPI design and business metric development  
- Data visualisation and dashboard design in Power BI  
- Analytical thinking and insight generation  

---

## Business Value

This project demonstrates how raw transactional data can be transformed into meaningful business insights, helping stakeholders:

- Understand revenue drivers  
- Identify high-performing product categories  
- Detect operational inefficiencies  
- Improve delivery performance and customer experience  

---

## Author

Matthew Tavakoli
