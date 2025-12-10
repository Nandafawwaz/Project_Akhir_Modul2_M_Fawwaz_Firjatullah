Final Project Module 2 – SaaS Sales Analysis

Project Overview

This project is part of the Capstone Project for Module 2 (Data Analysis).
The goal is to analyze a SaaS company’s sales dataset to identify drivers of profit and loss, as well as provide actionable recommendations to improve profitability.

As a data analyst, I positioned myself as if working in a real company, where insights from the analysis are presented to stakeholders to support business decision-making.

Business Problem
Although sales figures appear high, the company suffers losses with certain customers and products.
Key business question:

How can we improve product profitability based on Sales, Customer Segment, and Industry?

Dataset
SaaS-Sales

- Rows: 9,994
- Columns: 19

Main columns:
- Sales, Profit, Discount
- Region, Country, City
- Industry, Segment
- Product, Customer, Order Date

Data Cleaning
- Checked for missing values → none found.
- Checked for duplicates → none found.
- Converted date format to datetime type.
- Identified outliers in Profit/Discount:
  Outliers represent real customers with extreme losses/profits, not errors.
  Therefore, they were retained for business insight instead of being removed.

Analysis

Descriptive Statistics

- Overall KPIs: Total Sales, Total Profit, Profit Margin, Average Discount.
- Profit breakdown by Product, Region, Segment, Industry, Customer.
- Top 10 customers/products with negative profit.
- Discount distribution and its impact on profit margin.

Inferential Statistics
-Correlation between Discount % and Profit Margin.
 Result: The higher the discount, the lower the profit margin, significantly.

Insights

- Products: Big Ol Database and ContactMatcher often lead to losses.
- Regions: Japan & Sweden are consistently unprofitable markets.
- Segments: SMBs (Small & Medium Businesses) are riskier with lower profit margins.
- Discounts: Discounts above 15% → profit margins turn negative.
- Customers: Some high-sales customers remain unprofitable due to excessive discounts and high-cost products.

Recommendations

- Cap SMB discounts at ≤15%.
- Reprice products that consistently generate losses.
- Apply regional pricing adjustments in APJ & Sweden.
- Renegotiate contracts with the 20 worst-performing customers.
- Monitor profit margins closely during the sales process.

Tableau Public Link :
https://public.tableau.com/app/profile/fawwaz.firjatullah/viz/capstone_17557684845910/Dash_Overview?publish=yes
  
