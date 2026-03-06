# Retail Performance Intelligence Dashboard (Power BI)

An interactive Power BI dashboard analyzing e-commerce performance across traffic, conversion, product demand, and profitability.

This project demonstrates how business intelligence tools can be used to transform raw transactional data into actionable insights for decision makers.

---

# Dashboard Overview

The dashboard consists of four main sections designed to provide both high-level and detailed insights.

## Home
Navigation landing page providing access to all analytical views:
- Executive Summary
- Product Analysis
- Profitability Analysis

---

## Executive Summary

High-level overview of business performance including:

- Net Revenue
- Orders
- Sessions
- Conversion Rate
- Year-over-Year Growth
- Revenue Trends

This page helps executives quickly understand overall business performance.

---

## Product Analysis

Product-level insights including:

- Orders by Product
- Revenue by Product
- Refund Impact Analysis
- Product Demand Patterns
- Revenue vs Refund Scatter Analysis

This section identifies the most popular and problematic products.

---

## Profitability Analysis

Financial performance analysis including:

- Gross Profit
- Profit Margin by Product
- Cost vs Revenue Comparison
- Refund Impact on Profitability
- Profit Contribution by Product

Dynamic insights highlight key profit drivers and potential business risks.

---

# Key Insights

- The **Original Mr. Fuzzy** is the primary profit driver, generating the highest revenue and profit.
- **Birthday Sugar Panda** achieves the highest profit margin, indicating strong cost efficiency.
- Refund impact highlights potential product performance issues.
- Total gross profit generated across all products exceeds **€224K**.

---

# Data Model

The dashboard uses a **star schema data model** consisting of:

Tables
- `orders`
- `order_items`
- `order_item_refunds`
- `website_sessions`
- `products`
- `calendar`

This structure ensures efficient filtering and scalable analysis.

---

# Key Features

- Interactive navigation between dashboard pages
- Advanced DAX calculations for KPIs
- Dynamic insight generation
- Profitability and refund impact analysis
- Executive-focused data storytelling

---

# Tools Used

- Power BI
- DAX
- Data Modeling
- Data Visualization
- Business Intelligence
- Time Intelligence

---

# Project Files

Power BI file : https://drive.google.com/drive/u/0/folders/14BUNH2wH9oZAKFSFifJWbnQYvoRo0fhc
# Dataset 
https://mavenanalytics.io/data-playground/toy-store-e-commerce-database

