# BMW Sales Dashboard
![Pizza Sales Dashboard](assets/dashboard_preview.png)
# Overview

This project features a comprehensive BMW Sales Dashboard that provides insights into revenue performance, sales channels, product analytics, and geographical distribution. The dashboard presents key metrics in a visual format to help stakeholders understand sales trends and make data-driven decisions.

# Data Processing

**Data Modeling and Transformation**

Implemented data modeling to structure the raw sales data for optimal analysis

Created merge queries to combine multiple data sources including:

Yearly revenue data

Sales channel information

Product/car model details

Geographical sales distribution

Established relationships between different data tables to enable comprehensive analysis

# Dashboard Components
**1. Revenue Overview**

Total Revenue: $1.13 billion

Yearly Revenue Breakdown:

2019: $227.8M

2020: $226.0M

2021: $230.0M

2022: $228.6M

2023: $220.7M

**2. Revenue by Channel**

Online Sales: 33.12% of total revenue

Dealership Sales: 66.88% of total revenue (calculated)

**3. Most Expensive Cars**

Top premium models by price:

BMW M6: $7,881,199

BMW M2: $77,428.60

BMW 7 Series: $77,340.33

BMW iX3: $77,900.48

4. Sales by Car Series
Quantity sold by series:

BMW 3 Series: 210 units

BMW 4 Series: 190 units

BMW 5 Series: 174 units

BMW 6 Series: 192 units

**5. Geographical Distribution**

Sales by country (quantity sold):

United States: 1,019 units

Mexico: 1,017 units

Canada: 959 units

Nigeria: 755 units

Kenya: 660 units

Revenue by country:

United States: $76.8M

Mexico: $75.3M

Canada: $73.1M

Nigeria: $57.3M

Kenya: $59.3M

# Technical Implementation

**Data Sources**

The dashboard integrates multiple data sources through merge queries:

Sales transaction records

Product/car model information

Geographical data

Channel performance metrics

**Data Model**

Created star schema with fact and dimension tables

Established relationships between sales facts and dimension tables (time, product, geography, channel)

Implemented measures for calculated metrics like percentages and growth rates


# Tools Used
Data modeling and transformation tools Power Query

Data visualization platform Power BI

