# B2B Sales Analytics Dashboard

## Overview
This project analyzes a B2B transactional dataset to generate insights on sales performance, customer behavior, and operational efficiency. The outcome is a set of interactive dashboards for business decision-making.

---

## Dataset Description
The dataset consists of 7 relational tables:

- Customers  
- Employees  
- Offices  
- Orders  
- Order Details  
- Payments  
- Products  

**Time Period:** 2003–2005 (Static dataset)

---

## Objectives

- Analyze total revenue and profit  
- Identify best and worst performing products  
- Understand customer purchasing behavior  
- Measure operational efficiency (shipping delays)  
- Perform geographic sales analysis  
- Build dashboards for decision-making  

---

## Tech Stack

- Power BI / Excel  
- Power Query (ETL & Data Cleaning)  
- Power Pivot (Data Modeling)  
- DAX (KPIs & Measures)  

---

## Data Pipeline

1. **Data Extraction**  
2. **Data Cleaning (Power Query)**
   - Standardization  
   - Missing value handling  
   - Derived columns  

3. **Data Modeling (Power Pivot)**
   - Fact & dimension tables  
   - Relationships  

4. **Data Visualization**
   - Dashboard development  

---

## Feature Engineering

- Revenue = Quantity × Price  
- Profit = Revenue − Cost  
- Profit Margin  
- Customer Lifetime Value (approx.)  
- Shipping Delay  
- Customer Segmentation  
- Order Frequency  

---

## Dashboards

### 1. Sales Dashboard
- Total Revenue  
- Total Profit  
- Sales Trends  
- Top Products  

### 2. Customer Dashboard
- Customer Segmentation  
- Top Customers  
- Repeat Purchase Behavior  

### 3. Regional Dashboard
- Revenue by Geography  
- Territory Performance  

### 4. Salesperson Dashboard
- Sales by Employee  
- Customer Assignments  
- Follow-up Indicators  

---

## Key Insights

- Revenue is concentrated among a small set of customers  
- Product performance is uneven across categories  
- Regional sales disparities exist  
- Shipping delays impact operational efficiency  

---

## Limitations

- Static dataset (no real-time updates)  
- Missing customer contact details  
- No direct order-payment linkage  
- Limited historical range (3 years)  

---

## Future Improvements

- Integrate real-time data pipelines  
- Add customer enrichment (email, firmographics)  
- Implement predictive models (churn, demand forecasting)  
- Introduce customer scoring (LTV, loyalty index)  

---

## Author
**Bhawani Singh**
