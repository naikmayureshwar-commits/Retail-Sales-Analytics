Retail Sales Analytics --- MySQL
Project Overview
Retail Sales Analytics is a business-focused SQL project built in MySQL
to analyze retail transactions and generate actionable insights for
sales, product, customer, regional, channel, time, and profitability
decisions.
The project uses a 2025 retail transaction dataset containing 1,000
sales records and a separate customer master table containing 300
registered customers, including customers with no recorded purchases.
Business Objectives
- Measure overall sales and profitability
- Identify high-performing products, categories, regions, and channels
- Analyze customer purchasing behavior and repeat customers
- Identify inactive and high-value customers for reactivation
- Track monthly and quarterly sales performance
- Evaluate discount levels against profitability
- Identify high-sales but low-margin opportunities
- Support business recommendations using SQL-driven evidence
Analysis Covered
1. Dataset Overview
2. Data Quality Checks
3. Overall Business KPIs
4. Sales Performance
5. Product Analysis
6. Category Analysis
7. Regional Analysis
8. Customer Analysis
9. Channel Analysis
10. Time-Based Analysis
11. Profitability Analysis
12. Advanced Business Analysis
13. Final Business Insights
14. Business Recommendations
SQL Techniques Used
- SELECT, WHERE, HAVING, GROUP BY, ORDER BY
- SUM, COUNT, AVG, MIN, MAX, DISTINCT
- CASE expressions and conditional aggregation
- Date functions: MONTH, MONTHNAME, QUARTER, DATEDIFF, DATE_SUB
- Subqueries and Common Table Expressions (CTEs)
- INNER JOIN and LEFT JOIN
- Window functions
- LAG, ROW_NUMBER, and DENSE_RANK
- NULLIF and COALESCE
Key Business Questions
- Which products and categories generate the most sales and profit?
- Which regions contribute the most revenue?
- Which products have strong sales but weak margins?
- How does discounting affect profitability?
- What percentage of customers are repeat customers?
- Which high-value customers have become inactive?
- Which channels perform best overall and within each region?
- Which months show significant sales declines or growth?
- Where is the business overly dependent on a single category or
  product?
- Which areas should management prioritize for revenue growth and
  profit improvement?
Project Structure
Retail-Sales-Analytics/
├── SQL/
│   ├── Retail_Sales_Final_Analysis.sql
│   └── Retail_Sales_Practice.sql
├── Data/
│   ├── retail_sales_data.csv
│   └── Retail_Sales_Customers.csv
├── Report/
│   └── Retail_Sales_Analysis_Report.pdf
└── README.md


Business Recommendations
- Control excessive discounting where margins decline significantly.
- Reactivate high-value inactive customers.
- Protect inventory and profitability of top-performing products.
- Investigate regions with weaker margins.
- Replicate successful channel and regional strategies.
- Reduce over-dependence on a single product category.
- Use customer-segment analysis for targeted campaigns.
- Monitor monthly demand fluctuations.
- Track profit alongside sales instead of relying on revenue alone.
Tools
MySQL | MySQL Workbench | SQL | Git | GitHub
Exact KPI figures and final insights should be taken from the
validated outputs of Retail_Sales_Final_Analysis.sql.
