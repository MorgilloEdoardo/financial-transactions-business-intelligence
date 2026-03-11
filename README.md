# Financial Transactions Business Intelligence Dashboard

## Project Overview

This project presents an end-to-end Business Intelligence analysis of financial transaction data using Power BI.

The goal of the project is to transform raw transactional data into actionable insights that support business decision-making. The dashboard analyzes financial performance, customer behavior, account activity, and product performance through an interactive and structured reporting environment.

The project demonstrates skills in:

• Data modeling  
• KPI definition  
• Data visualization  
• Business analysis  
• Dashboard design

---

## Tools & Technologies

![Power BI](https://img.shields.io/badge/PowerBI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-FFB000?style=for-the-badge)
![Data Modeling](https://img.shields.io/badge/Data%20Modeling-4CAF50?style=for-the-badge)
![Business Intelligence](https://img.shields.io/badge/Business%20Intelligence-1E88E5?style=for-the-badge)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-8E24AA?style=for-the-badge)
![Analytics](https://img.shields.io/badge/Analytics-FF7043?style=for-the-badge)  

---

## Dashboard Structure

### Executive Overview
<img src="images/01_Executive_Overview.png" width="900">

Provides a high-level summary of the financial performance of the organization.

Key metrics include:

• Total Balance  
• Total Income  
• Total Expenses  
• Total Transactions  

The page highlights trends over time and provides an overview of transaction distribution by category.

---

### Transaction Analysis
<img src="images/02_Transaction_Analysis.png" width="900">

This page focuses on the analysis of transaction activity.

Key insights include:

• Transaction volume trends  
• Success rate of transactions  
• Average transaction value  
• Distribution of transactions by type and channel  

This section helps identify transaction behavior patterns across time and channels.

---

### Customer Analysis
<img src="images/03_Customer_Analysis.png" width="900">

The customer analysis page focuses on understanding customer behavior and value.

Main metrics include:

• Total customers  
• Transactions per customer  
• Average customer value  

The dashboard also highlights:

• Customer activity trends over time  
• Top customers by transaction volume  
• Customer value distribution

This section supports customer segmentation and value analysis.

---

### Product Performance
<img src="images/04_Product_Performance.png" width="900">

This page analyzes the performance of financial products.

The analysis focuses on:

• Product transaction volume  
• Total product value  
• Average product value  

A scatter analysis allows the identification of high-performing products by comparing transaction volume and total value.

---

### Account Overview
<img src="images/05_Account_Overview.png" width="900">

The account overview provides insights into account performance and distribution.

Key metrics include:

• Total accounts  
• Newly opened accounts  
• Average account balance  
• Total balance value  

The page also analyzes:

• Balance distribution across accounts  
• Transactions per account type  
• Account status distribution

---

## Data Model

The dashboard is built using a **Star Schema data model**, which improves performance and analytical flexibility.

Tables used in the model:

FactTransaction  
DimCustomer  
DimAccount  
DimProduct  
DimProductCategory  
DimProductSubCategory  
Calendar

This structure enables efficient filtering, aggregation, and multi-dimensional analysis.

---

## Key Metrics

The dashboard tracks several key performance indicators, including:

Total Balance  
Total Income  
Total Expenses  
Total Transactions  
Success Rate  
Average Transaction Value  
Customer Value  
Product Performance  

These KPIs provide a comprehensive overview of financial and operational performance.

---

## Business Questions

The dashboard helps answer important business questions such as:

• How are income and expenses evolving over time?  
• Which customers generate the highest transaction value?  
• Which products drive the largest transaction volumes?  
• How are transactions distributed across channels?  
• How are accounts distributed by type and balance?

---

## Dashboard File

The Power BI dashboard file is included in the repository:

financial_dashboard.pbix

You can open the file using **Microsoft Power BI Desktop** to explore the interactive report.

---

## Author

Edoardo Morgillo  
Data Analyst

LinkedIn  
https://www.linkedin.com/in/edoardo-morgillo

GitHub  
https://github.com/MorgilloEdoardo
