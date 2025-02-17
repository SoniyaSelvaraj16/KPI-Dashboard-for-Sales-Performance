Sales Insight Dashboard using Power BI

Overview

This Sales Insight Dashboard was built using Power BI to help AtliQ Hardware, a computer hardware & peripherals company, analyze sales performance across different markets, customers, and products. The dashboard provides a visual representation of key business metrics, enabling the Sales Director to make data-driven decisions instead of relying on raw Excel data.

This project is based on the Codebasics YouTube Playlist, which can be found here.

Problem Statement

AtliQ Hardware operates across multiple branches in India and faces challenges in understanding business performance due to declining sales. The Sales Director struggles to get real-time insights from regional managers, as interpreting raw sales data in Excel is difficult and inefficient.

Challenges Faced:

Lack of real-time sales tracking.
Difficulty in understanding revenue trends.
No clear visibility on high/low-performing products and markets.

Solution

To tackle these challenges, the Sales Director decided to implement a Power BI Dashboard, transforming raw sales data into interactive visualizations. A data team was hired to build a solution that would provide real-time, data-driven insights for better decision-making.

Project Planning:
The team used the AIMS Grid project management tool to define:

Purpose: Understand sales trends and challenges.
Stakeholders: Sales Director, Regional Managers, Data Team.
End Result: A fully interactive Power BI dashboard.
Success Criteria: Improved decision-making based on data insights.

Steps Followed

1️⃣ AIMS Grid for project planning.
2️⃣ Used MySQL to retrieve sales data from the database.
3️⃣ Data Cleaning using Power Query in Power BI.
4️⃣ ETL Process: Extract, Transform, Load to prepare data.
5️⃣ Created DAX Measures for KPIs and visualizations.
6️⃣ Currency Conversion to standardize all transactions.
7️⃣ Data Validation to ensure accuracy.
8️⃣ Data Modeling & Visualization in Power BI.

 Customizations & Enhancements
 
Fixed (Blank) issue in the Products Table by modifying product data (Prod280 - Prod339).
Merged sales_transaction table with additional columns like profit margin and cost price.

Key Insights from the Dashboard

Total Sales Performance

Revenue: ₹11M
Sales Quantity: 7,987

Market-Wise Analysis

Top Market by Revenue: Mumbai (₹6.4M)
Second Highest Market: Delhi NCR (₹2.9M)
Highest Sales Quantity Market: Delhi NCR (3.5K)

Customer & Product Analysis

Top Customer: Electricalsytical (₹2.29M Revenue)
Best-Selling Product: Prod018 (₹6.4M Revenue)

Revenue Trends

Revenue Dip Observed: Around June 2018 and Late 2019
Peak Revenue Observed: Around Mid-2018

Key Learnings

✅ Understanding real business datasets.
✅ Writing complex SQL queries for analysis.
✅ Connecting MySQL database to Power BI.
✅ Cleaning & transforming data using Power Query.
✅ Using DAX functions to create meaningful KPIs.
✅ Designing analytical visuals & reports.

Final Dashboard Output
The Dashboard KPI Page includes:

<img width="565" alt="image" src="https://github.com/user-attachments/assets/1d926e21-36b2-4c2e-b493-925902ded4d4" />



Total Revenue & Sales Quantity
Revenue by Market & Customer
Sales Quantity by Product
Profit Margin % by Market
Trend Analysis (Yearly, Monthly, Quarterly)

Technologies Used

Power BI for Data Visualization
MySQL for Data Extraction
Excel/CSV for Data Preprocessing

DAX (Data Analysis Expressions) for KPIs

How to Use

Open the Power BI file and connect to your data source.
Explore the interactive dashboard and use filters to analyze insights.

Contributing
Feel free to fork this repo, raise issues, or submit pull requests to improve the dashboard.

License
This project is open-source under the MIT License.

