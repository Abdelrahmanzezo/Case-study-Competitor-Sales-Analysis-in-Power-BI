📊 Competitor Sales Analysis – Power BI Case Study
Overview:
This case study simulates a real-world scenario where I built a comprehensive Power BI report to analyze sales performance and market share—both internally (by product and category) and externally (against competing manufacturers). The project showcases the full BI lifecycle, including data integration, transformation, modeling, DAX calculations, and interactive dashboards.

🔧 Tools & Skills Used:
Power BI Desktop

Power Query Editor

DAX for KPIs and time intelligence

Data modeling using star schema

AI visuals and key influencers

🧩 Data Preparation & Modeling:
Combined multiple international sales CSV files into one dataset.

Merged the result with the main fact sales table to build the competitor sales dataset.

Cleaned and transformed data in Power Query by handling nulls, changing data types, and standardizing formats.

Resolved relationship issues between the Sales and Geography tables by creating a new column (Country + ZipCode) in both, allowing a proper one-to-many relationship.

Built a star schema model linking tables: Sales, Products, Manufacturer, Geography, and Date.

Created a custom Date table using DAX for time-based analysis.

📈 Metrics & KPIs (Built with DAX):
Revenue

PY Sales (Previous Year Sales)

% Growth (Year-over-Year)

Sintec Market Share (Manufacturer-level comparison)

% GT Sum of Revenue

Units Sold

📋 Dashboard Insights:
Page 1: Competitor Sales Overview

KPI cards showing current vs last year’s revenue.

Sintec's market share: 19.63%.

Product and segment breakdowns (Youth, Mix, Rural, etc.).

Revenue by country: USA ($51M), Japan ($11M), and others.

Revenue and % growth trend from 2019 to 2021, with notable growth in 2021.

Page 2: Deep Dive with Key Influencers

Total revenue: $51.47M | PY Sales: $30.71M | Units Sold: 143K | Growth: 67.63%

Tree breakdown: Category → Segment → Product

AI-powered Key Influencers visual showed:

Sintec UC-19, UM-01, and UE-15 are top drivers of revenue.

Urban category regions perform best in sales.
