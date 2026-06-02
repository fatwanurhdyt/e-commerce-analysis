# E-Commerce Performance Analysis | Brazil 2017–2018

> **A data analyst portfolio project analyzing Brazilian e-commerce transactions using Python (Jupyter Notebook) and Tableau. The dataset covers 110,000+ orders across 2017–2018, exploring revenue trends, product performance, customer satisfaction, and delivery efficiency.**

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Business Questions](#business-questions)
- [Analysis Workflow](#analysis-workflow)
- [Dashboard Preview](#dashboard-preview)
- [Key Findings](#key-findings)
- [Insights](#insights)
- [Business Recommendations](#business-recommendations)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Tools](#tools)
- [About](#about)

---

## Overview
End-to-end exploratory data analysis of Brazilian e-commerce transactions from Olist (2017–2018), covering revenue trends, product performance, customer satisfaction, and delivery efficiency across 110.042 orders.

This project demonstrates full data analytics workflow:
data cleaning → EDA → visualization → business insight.

---

## Dataset

- **Source:** [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) — Kaggle
- **Period:** January 2017 – August 2018
- **Records:** 110,422 orders
- **Key fields:** `order_id`, `payment_value`, `review_score`, `order_status`, `customer_state`, `delivery_date`

---

## Business Questions

1. **How did monthly revenue trend from 2017–2018?**
2. **Which product categories drove the most sales?**
3. **What is the customer satisfaction distribution?**
4. **Which states generated the most orders?**
5. **How efficient was the delivery process?**

---

## Analysis Workflow

### 1. Business Understanding
- Defined the business objective of analyzing e-commerce performance in Brazil during 2017–2018.
- Formulated key business questions related to revenue trends, product category performance, customer satisfaction, order distribution, and delivery efficiency.
- Set the analysis focus on identifying performance drivers and operational improvement opportunities.

### 2. Data Collection
- Used the Brazilian E-Commerce Public Dataset by Olist from Kaggle.
- Loaded multiple related tables, including orders, order items, payments, reviews, customers, and product category data.

### 3. Data Understanding
- Explored the structure of each table.
- Identified key variables related to revenue, orders, customer location, product category, review score, and delivery status.
- Checked data types, missing values, duplicated records, and relationships between tables.

### 4. Data Cleaning & Preparation
- Handled missing values in relevant fields.
- Standardized date columns for order purchase, estimated delivery, and actual delivery.
- Merged related tables into a single analytical dataset.
- Created a cleaned master dataset for analysis and Tableau visualization.

### 5. Feature Engineering
- Calculated total revenue based on customer payment value.
- Created delivery-related metrics such as delivery duration and on-time delivery status.
- Extracted monthly order period to analyze revenue trends over time.
- Prepared product category, state, review score, and delivery performance fields for dashboard analysis.

### 6. Exploratory Data Analysis
- Analyzed monthly revenue trends from 2017 to 2018.
- Identified top product categories by revenue.
- Examined customer satisfaction through review score distribution.
- Analyzed order distribution by customer state.
- Evaluated delivery performance using average delivery days and on-time delivery rate.

### 7. Dashboard Development
- Exported the final cleaned dataset into CSV format for Tableau.
- Built an interactive Tableau dashboard to summarize revenue, orders, review score, product category performance, state-level orders, and delivery efficiency.

### 8. Insights & Recommendations
- Summarized key business findings from the dashboard.
- Developed business recommendations related to revenue growth, product focus, customer satisfaction, and delivery improvement.

---
## Dashboard Preview

![Dashboard Preview](assets/dashboard_preview.png) 
🔗 [View on Tableau Public](https://public.tableau.com/app/profile/fatwa.nurhidayat/viz/E-CommercePeformanceDashboard/E-CommerceSalesAnalysisDashboard) 

---

## Key Findings

| # | Question | Finding |
|---|----------|---------|
| 1 | Revenue Trend | Revenue grew steadily throughout 2017, peaking at **BRL 1.55M** in Nov 2017, with a slight decline into mid-2018 |
| 2 | Top Categories | **Bed, Bath & Table** led with BRL 1.70M, followed by Health & Beauty (1.62M) and Computer Accessories (1.56M) |
| 3 | Customer Satisfaction | **63,013 orders (57%)** rated 5/5 — overall avg score **4.08/5.00**, indicating high satisfaction |
| 4 | Orders by State | **São Paulo (SP)** dominates with 46,529 orders, followed by RJ (14,183) and MG (12,936) |
| 5 | Delivery Efficiency | On-time rate of **92.6%** overall; SP delivers in ~8 days while remote states like AM/RR average 25–28 days |

---

## Insights

### 1. Revenue showed strong growth from 2017 to 2018

Monthly revenue increased significantly from early 2017 and reached its highest point in November 2017. The 2018 revenue level remained higher than the 2017 average, indicating stronger business performance and higher transaction volume.

However, the slight decline after the peak suggests that revenue growth was not fully sustained, so the business may need to evaluate seasonality, campaign timing, and customer retention strategies.

### 2. Revenue is concentrated in several product categories

The top revenue contributors were Bed, Bath & Table, Health & Beauty, and Computer Accessories. These categories generated the highest payment value and became the main drivers of marketplace revenue.

This indicates that the business depends heavily on a limited number of product categories, which can create growth opportunities but also concentration risk if demand in these categories decreases.

### 3. Customer satisfaction is generally high

Most customers gave a review score of 5, and the average review score reached 4.08 out of 5.00. This shows that the overall customer experience was positive.

However, the presence of low review scores indicates that some customers still experienced issues, likely related to delivery delays, product quality, or seller service.

### 4. Orders are highly concentrated in São Paulo

São Paulo generated the largest number of orders, far above other states such as Rio de Janeiro and Minas Gerais. This suggests that the e-commerce business has a strong customer base in major urban and economically active regions.

At the same time, lower order volume in other states may indicate untapped market potential outside the main customer concentration areas.

### 5. Delivery performance is strong overall but varies by state

The overall on-time delivery rate reached 92.6%, showing that most orders were delivered within the estimated delivery date.

However, delivery performance varied across states. Some remote states had longer average delivery days and lower on-time rates, indicating that logistics efficiency remains a challenge in certain regions.

### 6. Delivery speed may influence customer satisfaction

The high average review score suggests a generally positive customer experience, while delayed deliveries in some states may contribute to lower satisfaction for specific customer groups.

Improving delivery performance in states with longer delivery times can help maintain customer satisfaction and reduce negative reviews.

---

## Business Recommendations

### 1. Strengthen high-performing product categories

The company should prioritize marketing, inventory planning, and seller support for top revenue categories such as Bed, Bath & Table, Health & Beauty, and Computer Accessories.

These categories are major revenue drivers, so improving their availability, pricing strategy, and promotional campaigns can help sustain revenue growth.

### 2. Reduce dependency on top categories

Although several categories generate strong revenue, the business should also develop mid-performing categories with growth potential.

This can reduce revenue concentration risk and create more balanced marketplace growth across product segments.

### 3. Improve delivery performance in remote states

States with longer average delivery times and lower on-time rates should be prioritized for logistics improvement.

The company can evaluate delivery partners, optimize shipping routes, improve fulfillment planning, or set more realistic estimated delivery dates for remote areas.

### 4. Maintain customer satisfaction by reducing low-score experiences

Since most customers gave high review scores, the company should focus on reducing the causes of low ratings.

Further analysis should be conducted on orders with review scores of 1 or 2 to identify whether dissatisfaction is mainly caused by late delivery, product issues, or seller service.

### 5. Expand growth outside São Paulo

São Paulo dominates total orders, but other states may still offer market expansion opportunities.

The company can run targeted marketing campaigns, improve delivery coverage, and increase seller participation in states with lower order volume but potential demand.

### 6. Use monthly revenue trends for campaign planning

Revenue increased strongly during certain months, especially around the peak period in late 2017.

The company should use monthly trend analysis to plan seasonal campaigns, inventory preparation, and logistics capacity before high-demand periods.

### 7. Use the dashboard as a business monitoring tool

The Tableau dashboard can help monitor revenue, order volume, customer satisfaction, product category performance, and delivery efficiency.

This dashboard can support business teams in identifying performance changes quickly and making data-driven operational decisions.

---

## Project Structure

```
e-commerce-analysis/
│
├── assets/
│   └── dashboard_preview.png
│
├── dashboard/
│   └── e-commerce peformance dashboard.twbx                          # Tableau workbook                   
│
├── notebook/
│   └── ecommerce-sales-analysis.ipynb                                # Data cleaning, EDA, feature engineering  
│
├── tableau/
│   └── tableau_master.csv                                            # Cleaned dataset used for Tableau
│
├── README.md
└── requirements.txt
```

---

## How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/fatwanurhdyt/E-Commerce-Analysis.git
   cd e-commerce-analysis
   ```

2. Install dependencies
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```

3. Open the notebook
   ```bash
   jupyter notebook notebook/ecommerce-sales-analysis.ipynb
   ```

4. For the dashboard, open `tableau_master.csv` in Tableau or visit the Tableau Public link above.

---

## Tools

| Tool | Purpose |
|------|---------|
| Python (Pandas, Matplotlib, Seaborn) | Data cleaning & EDA |
| Jupyter Notebook | Analysis & documentation |
| Tableau Public | Interactive dashboard |
| GitHub | Version control & portfolio hosting |

---

## Author

**Fatwa Nurhidayat**
- GitHub: [@fatwanurhdyt](https://github.com/fatwanurhdyt)
- LinkedIn: [linkedin.com/in/fatwanurhdyt](https://linkedin.com/in/fatwanurhdyt)
- Email: [fatwa.nrhdyt@gmail.com](mailto:fatwa.nrhdyt@gmail.com)
