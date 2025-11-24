📊 Customer Behaviour Analysis

This project explores and analyzes customer behaviour using Python, PostgreSQL, and Power BI. The goal is to understand purchasing patterns, segment customers, and generate insights that support business decisions and marketing strategies.

📁 Project Overview

The project follows a complete data analytics workflow:

Data Cleaning & Preprocessing (Python)

Handling Missing Values & Data Quality Enhancements

Data Modeling & Feature Engineering

Loading and Querying the Data in PostgreSQL

Insight Generation using SQL

Interactive Dashboards in Power BI

This end-to-end pipeline mirrors real-world analytics processes.

🛠️ Tools & Technologies
Languages & Libraries

Python

Pandas

NumPy

Database

PostgreSQL

SQL queries for segmentation, trend analysis, and summary statistics

Visualization

Power BI (interactive dashboards)

🔧 Steps Performed
1. Data Cleaning (Python)

Removed duplicates and invalid entries

Standardized column formats (date, number, category fields)

Fixed inconsistent string values

Performed outlier detection and correction

2. Handling Missing Values

Used statistical imputation (mean/median)

Category-based filling for product or region fields

Verified data completeness after transformation

3. Data Modeling

Created meaningful features:

Customer Recency

Purchase Frequency

Monetary Value (RFM Metrics)

Category-Level Preferences

Time-based features (month, quarter, season)

Built a clean fact–dimension structure for PostgreSQL

4. Database Integration (PostgreSQL)

Loaded cleaned datasets into PostgreSQL

Created tables, relationships, and indexes

Used SQL queries for:

Customer segmentation

Revenue analysis

Purchase trend patterns

Product-level performance

5. Visualization (Power BI)

Created interactive dashboards including:

Revenue Trends

Top-Spending Customer Profiles

Category & Product Performance

RFM Segmentation Visuals

Region/Time-Based Behaviour Patterns

![image alt](https://github.com/nagarjun17/customer-behaviour-data-analysis/blob/12b624b5cd7b49b97b61db941b95907672c06106/customer_behavior_dashboard.jpg)

📈 Key Insights (Replace with your findings)

Identified top segments contributing most to revenue

Found repeat purchase patterns across specific product categories

Detected seasonal and monthly demand trends

Created customer cohorts to track retention

Highlighted at-risk vs loyal customer groups using RFM scores
