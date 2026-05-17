# E-Commerce-Customer-Churn-Analysis

## Tools Used
- SQL Server
- Excel
- Power BI

## Skills Demonstrated
- SQL Query Writing
- CTEs & SQL Views
- Data Cleaning
- DAX Measures
- Data Visualization
- Customer Segmentation
- Churn Analysis
- Dashboard Design
- Business Storytelling

## Dataset
E-Commerce Customer Dataset — Kaggle

- Records: 5,630 customers
- Features: 20 columns

---

# Problem Statement

An e-commerce company is losing 16.84% of its customers every month. This analysis identifies which customers are at highest risk of churning, what behavioral and demographic patterns drive churn, and how to segment customers into risk tiers for targeted retention action.

---

# Key Findings

- Overall churn rate: 16.84% — 948 out of 5,630 customers
- Customers in first 3 months churn at 41.86% — 2.5x the overall average
- Complaint filers churn at 31.67% vs 10.93% for non-complainers — nearly 3x higher
- Critical Risk segment (Tenure ≤ 3 months + complaint filed): 66.09% churn rate — 4x overall
- COD payment users churn at 24.90% vs 14.21% for credit card users
- 422 active customers identified as At Risk requiring immediate intervention

---

# Project Workflow

### Step 1 — Excel
- Cleaned 5,630 customer records.
-  Removed duplicates.
-  Handled null values.
-   Created Tenure_Band calculated column.
### Step 2 — SQL Server 
- Wrote 12+ analytical SQL queries
- Built CTE-based risk segmentation model.
-  Created SQL VIEW (vw_HighRiskCustomers)

 ### Step 3 — Power BI
- Built 4-page dashboard.
- Wrote 8 DAX measures.
- Added cross-page slicers and drill-through customer table.
  

## Dashboard Pages
- Page 1 — Overview: 5 KPI cards, churn by tenure, payment mode, city tier, complaint, order category
- Page 2 — Customer Behaviour: Scatter plot, order count comparison, cashback comparison, satisfaction scores, payment mode table
- Page 3 — Risk Analysis: Risk segment combo chart, top risk customer table, churn by satisfaction and complaint line chart
- Page 4 — Insights: 4 finding cards with actions and data-driven recommendations

## Recommendations
- Onboarding campaign for 0–3 month customers with milestone cashback rewards
- 24-hour complaint resolution SLA for early-tenure customers
- COD-to-digital payment incentive — ₹50 for first digital payment
- Win-back campaign for customers inactive 25+ days
