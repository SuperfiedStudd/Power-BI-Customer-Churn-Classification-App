# Power-BI-Customer-Churn-Classification-App  

[View on Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.churn-rate-customer-classification?tab=Overview)  

[![Watch the Demo](https://img.youtube.com/vi/sbiGt5fZSfU/0.jpg)](https://youtu.be/sbiGt5fZSfU?si=hrIPNkIz8Eo7LW_W)  

---

## Overview  

Customer retention is one of the most critical indicators of long-term business sustainability. The **Customer Churn & Classification Dashboard** enables businesses to proactively monitor customer engagement trends, identify risk segments, and strengthen retention strategies.  

By analyzing churn rates, rework request levels, and customer tenure breakdowns, this dashboard offers a comprehensive view of customer behavior. It empowers sales and strategy teams to focus retention efforts, tailor product offerings, and understand customer value distribution.  

---

## Technical Framework  

This dashboard is built on a structured Excel dataset capturing customer activity, tenure, product usage, and churn indicators.  

**Key components:**  
- **Data Source:** Excel files recording customer profiles, last order dates, product categories, deal size, tenure, and rework request levels  
- **Data Preparation:** Conducted in Power Query to calculate churn flags, classify tenure, and align dimensions like deal size and payment type  
- **Data Model Dimensions:**  
  - Customer Tenure  
  - Product Category  
  - Rework Request Level (High / Medium / Low)  
  - Deal Size  
  - Payment Type  
  - Order Activity Date (used for churn calculation)  

The structure is flexible and can be scaled to incorporate CRM, ERP, or customer support system data.  

---

## Interactive Filters  

Filters enable targeted insights and segmentation of customer data:  
- **Customer Tenure:** Segment customers by loyalty—New (0–1 yr), Emerging (1–3 yrs), Established (3–5 yrs), Loyal (5+ yrs)  
- **Deal Size:** Filter by contract value tiers to explore trends across different customer segments  
- **Payment Type:** Understand retention patterns by payment method and identify transactional friction  

These filters support sales teams and account managers in customizing outreach strategies and prioritizing retention actions.  

---

## Dashboard Highlights  

**KPI Cards – Customer Overview**  
- Active Customers: Count of customers with orders in the recent active window  
- Churn Rate (%): Percentage of customers inactive for over 6 months  
- Inactive Customers (Last 6 Months): Absolute count of potentially churned customers  
- Total Customers: Total base of customers tracked in the system  

**Table – Rework Requests vs. Customer Count**  
Groups customers by rework levels (High, Medium, Low), showing potential links between service issues and churn risk.  

**Donut Chart – Customer Distribution by Tenure**  
Breaks down the customer base by age of relationship, highlighting opportunities to nurture new accounts and reward long-standing ones.  

**Bar Chart – Customer Count by Product Category**  
Identifies which product categories have the highest customer engagement—useful for prioritizing inventory, marketing, and service improvements.  

This Power BI dashboard empowers customer-facing teams to turn raw retention data into proactive engagement strategies—reducing churn, deepening relationships, and driving lifetime customer value.  

---

## Screenshots  

### Dashboard Overview  
![Dashboard Overview](https://github.com/SuperfiedStudd/Power-BI-Customer-Churn-Classification-App/blob/main/docs/dashboard_overview.png?raw=true)  

### KPIs  
![KPIs](https://github.com/SuperfiedStudd/Power-BI-Customer-Churn-Classification-App/blob/main/docs/kpis.png?raw=true)  

### Customer Classification Graph  
![Customer Classification Graph ](https://github.com/SuperfiedStudd/Power-BI-Customer-Churn-Classification-App/blob/main/docs/custclass.png?raw=true)  

---

## How to Use  

This repository is intended as a showcase:  
1. Watch the demo video above for a walkthrough.  
2. Explore the screenshots for dashboard views.  
3. Try the published app directly on [Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.churn-rate-customer-classification?tab=Overview).  
   - You can download and play around with the app if you have a school or work account that supports Microsoft apps.  

---

## Why It Matters  

Retaining customers is far more cost-effective than acquiring new ones. This dashboard enables organizations to detect churn risks early, uncover hidden service issues, and strengthen customer relationships—maximizing lifetime value and long-term business growth.  

---

## Author  

Developed by **Jasjyot Singh**  
Contact: jasjyotsingh.work@gmail.com  
