Customer Retention & Revenue Optimization Analytics

End-to-End Food Delivery Customer Intelligence Case Study

📌 Project Overview

This project develops a structured customer intelligence framework to evaluate retention performance, churn risk, and revenue exposure for a food delivery platform.

The solution integrates:

RFM Segmentation

Churn Risk Modeling (90-day inactivity logic)

Revenue-at-Risk Quantification

Promotional Impact Analysis

Monthly Revenue Trend Forecasting

Interactive Power BI Dashboard

The objective is to transform raw transactional data into actionable business insights.

📊 Business Problem

Food delivery platforms experience customer churn that directly impacts revenue stability.

Key questions addressed:

What is the overall churn rate?

Which customer segments generate the highest revenue?

How much revenue is at risk due to churn?

Do promotional users churn less?

Which risk tiers require immediate intervention?

🧠 Analytical Approach

1️⃣ Data Preparation (Excel)

Cleaned and structured transaction-level order data

Generated customer-level aggregation

Created calculated fields for Revenue, Frequency, and Recency

2️⃣ RFM Segmentation Model

Customers were scored using:

Recency (Last order gap)

Frequency (Order count)

Monetary (Total spend)

Segments identified:

Champions

Loyal Customers

Potential Loyalists

At Risk

Recent Customers

3️⃣ Churn Definition

Churn was defined as:

Customers inactive for more than 90 days from analysis date.

4️⃣ Revenue at Risk Analysis

Revenue exposure calculated by isolating churned customers' contribution to total revenue.

5️⃣ Promotional Impact Evaluation

Churn rates compared between:

Promo Users

Non-Promo Users

6️⃣ Sales Trend Forecasting

3-Month Moving Average applied to identify revenue patterns and seasonality.

7️⃣ Power BI Dashboard Development

Interactive dashboard built to visualize:

KPI metrics

Monthly revenue trends

Segment-wise revenue contribution

Risk-tier distribution

Churn status breakdown

Geographic revenue distribution

📈 Key Insights

Total Customers: 588

Churned Customers: 234

Churn Rate: 39.8%

Revenue at Risk: 28.5% of total revenue

Revenue concentration skewed toward Champions and Loyal Customers

High churn concentration in Moderate & Low Risk tiers

🛠 Tools Used

Microsoft Excel (Data Modeling & RFM Engine)

Power BI (Dashboard Development)

DAX (Custom Measures & KPI Calculations)

📂 Repository Structure

1_data/ → Raw dataset  

2_excel_model/ → RFM & churn calculation engine  

3_powerbi_dashboard/ → Interactive BI dashboard  

4_dashboard_preview/ → Dashboard screenshots  

5_documentation/ → Project methodology documentation  

🎯 Business Impact

This project demonstrates how structured customer analytics can:

Quantify revenue exposure

Identify high-value retention targets

Prioritize intervention segments

Support strategic decision-making.
