🎯 Project Concept

Title:

Retail Performance & Profitability Intelligence Dashboard

Business Goal:
Help leadership understand revenue growth, customer behavior, and profitability drivers.

📊 Dashboard Structure (Recruiter-Friendly Layout)
🔹 Page 1 – Executive Overview

KPIs:

Total Revenue

Gross Profit

Profit Margin %

YoY Growth

Avg Order Value

Customer Count

Visuals:

Revenue Trend (YoY comparison)

Category Contribution %

Region Map

Monthly Growth Waterfall

DAX to Showcase:

YTD, MTD

YoY %

Running total

Dynamic KPI switch

Conditional formatting

This page should look clean and executive-level.

🔹 Page 2 – Customer Analytics

Show:

RFM Segmentation (Recency, Frequency, Monetary)

Repeat vs New Customers

Customer Lifetime Value (CLV)

Cohort retention (monthly signup vs repeat purchase)

This is where you stand out from most portfolios.

Advanced Touch:

Customer risk flag (declining purchase frequency)

🔹 Page 3 – Product & Profitability

Show:

Top/Bottom products

Profit margin by category

Discount impact analysis

Contribution analysis (Pareto 80/20 rule)

Price sensitivity (what-if parameter)

Add:

Drill-through from category → product → transaction

🔹 Page 4 – Forecast & Scenario Modeling

Use:

Built-in forecasting

What-if parameter for:

Discount %

Sales increase %

Cost increase %

Show impact on:

Profit

Margin

Revenue

This screams: “I understand business impact.”

📁 Where to Get Data

Use:

Kaggle Superstore dataset (upgrade it)

Or generate synthetic ERP-style data

Or combine retail + inflation data (more advanced)

🧠 Data Model (IMPORTANT)

Use proper star schema:

Fact Table:

Sales (OrderID, DateKey, ProductKey, CustomerKey, Revenue, Cost)

Dimension Tables:

Date

Customer

Product

Geography

Create:

Proper Date table

Relationships

Avoid bi-directional relationships unless needed

Recruiters check this.

🔥 DAX You Should Definitely Include

Revenue YTD

Revenue YoY %

Rolling 12 Months

Customer Lifetime Value

Rank by Sales

% Contribution

Moving Average

Dynamic title measures

Selected value logic

If you can explain these confidently, you look solid.

🎨 Design Tips (Make It Look Senior)

Use muted theme (dark or minimal white)

Limit to 3–4 main colors

Proper spacing

Consistent KPI card style

Avoid overcrowding

Use tooltips smartly

Think “corporate dashboard”, not “Power BI gallery”.
