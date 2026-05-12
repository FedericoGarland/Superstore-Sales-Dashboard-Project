# US-Wide Superstore Sales Analytics Dashboard (Power BI, DAX, Data Modeling)

## Overview
Interactive sales analytics dashboard developed in Power BI to analyze the performance of a US-wide superstore and support data-driven commercial decision-making.

The project focuses on identifying revenue drivers, sales trends and areas of opportunity through the analysis of key business KPIs such as Revenue, Average Ticket Value (ATV), Units Per Transaction (UPT), Orders, Sold Units and Customer Count.

A dimensional star schema model was designed and implemented in Power BI using DAX measures, time intelligence calculations and interactive visualizations to enable drill-down analysis across multiple business dimensions including category, subcategory, product, state and city.

Key components include:
- Star schema dimensional data modeling
- Interactive Power BI dashboard
- KPI tracking and year-over-year analysis
- Advanced DAX measures and time intelligence
- Dynamic filtering and drill-down analysis
- Sales performance analysis by geography and product hierarchy
- Business recommendations based on analytical findings

---

# Architecture

### Analytics Workflow
CSV Dataset → Power Query → Star Schema Semantic Model → DAX Measures → Power BI Dashboard

### Dashboard
![Dashboard](images/dashboard.png)

---

# Tech Stack
- Power BI
- DAX
- Power Query (M)
- Data Modeling
- Excel
- Time Intelligence
- Data Visualization

---

# Business Problem
Retail businesses generate large volumes of transactional sales data, but often lack:

- Centralized KPI monitoring
- Consistent performance measurement
- Visibility into revenue drivers
- Drill-down analytics by geography and product hierarchy
- Actionable insights for improving profitability

This limits the ability of commercial teams to optimize sales strategies and identify operational opportunities for business growth.

---

# Solution
An interactive analytics dashboard was developed in Power BI to:

- Monitor sales KPIs and commercial performance
- Compare current year vs previous year performance
- Analyze trends across states, cities, categories and products
- Detect declines in key metrics such as ATV and UPT
- Identify underperforming business segments
- Support commercial strategy design with actionable insights

The solution includes:
- Dimensional star schema modeling
- Advanced DAX calculations
- Time intelligence measures
- Dynamic filtering and drill-through capabilities
- Interactive visual analytics

---

# Data Modeling

The dataset was modeled using a star schema architecture composed of:

## Fact Table
- Fact_Sales

## Dimension Tables
- Dim_Date
- Dim_Products
- Dim_Category
- Dim_Subcategory
- Dim_Customer
- Dim_Geography

A dedicated calendar table was created to support time intelligence calculations and year-over-year analysis.

Bidirectional filtering was avoided to prevent ambiguity and ensure model accuracy and performance.

---

# KPI Design

The dashboard tracks multiple business KPIs including:

- Revenue
- Sold Units
- Customer Count
- Orders
- Average Ticket Value (ATV)
- Units Per Transaction (UPT)

Advanced DAX measures were developed to:
- Compare Current Year vs Previous Year
- Calculate YoY growth percentages
- Compute moving averages
- Enable dynamic time filtering
- Analyze metrics across multiple business dimensions

DAX techniques used include:
- `CALCULATE`
- Time intelligence functions
- Variables
- Conditional logic
- Ranking functions
- Dynamic filtering

---

# Dashboard Features

## Interactive Analytics
The dashboard enables users to:
- Filter by state, city, category and subcategory
- Drill down into specific products and regions
- Compare current year vs previous year metrics
- Analyze performance trends over time

## Dynamic Measures
Features include:
- Dynamic moving averages
- KPI cards
- Time-based trend analysis
- Geographic performance analysis
- Product segmentation

## Visualizations
- KPI cards
- Line charts
- Bar charts
- Tables
- Slicers
- Trend analysis visuals

---

# Key Findings

## Revenue Performance
- Revenue increased by 25% year-over-year
- Orders increased by 42%
- Most business metrics grew between 30–40%

However:
- Average Ticket Value (ATV) decreased by 12%
- Units Per Transaction (UPT) decreased by 2.5%

This indicates that although transaction volume increased, each order generated less revenue on average.

---

## Product Mix Analysis
Analysis revealed a shift toward lower-priced products:
- Low-price product sales increased significantly
- High-price product participation declined proportionally

This negatively impacted:
- Average revenue per order
- Overall profitability growth

---

## Geographic Insights
Key underperforming regions and product segments were identified, including:
- Rhode Island
- Nevada
- Indiana
- Michigan

Specific subcategories such as:
- Binders
- Copiers
- Labels

showed significant ATV and revenue declines.

---

# Business Value

This dashboard enables:
- Faster commercial analysis
- Identification of revenue optimization opportunities
- Data-driven sales strategy design
- Executive KPI monitoring
- Geographic and product-level performance tracking

Potential commercial actions supported by the analysis include:
- Upselling strategies
- Cross-selling initiatives
- Bundle offers
- Product mix optimization
- Regional sales interventions

---

# Key Techniques
- Dimensional data modeling
- Star schema design
- Advanced DAX calculations
- Time intelligence analysis
- Interactive dashboard design
- KPI development
- Commercial performance analytics

---

# 🔗 Links
- 🚀 [Portfolio Website](https://federicogarlandportfolio.github.io/FedericoGarlandWebsite/)
- 💼 [LinkedIn Profile](https://www.linkedin.com/in/federico-garland/)
- 📂 [GitHub Profile](https://github.com/FedericoGarland)
