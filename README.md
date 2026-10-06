# Energy Consumption Analysis Using SQL

## Project Overview
The Energy Consumption Analysis project focuses on analyzing global energy-related data using MySQL. The project explores energy production, energy consumption, carbon emissions, GDP, and population across different countries and years.

By using SQL queries, the project identifies country-wise comparisons, global trends, emission patterns, and relationships between energy usage, economic growth, and population. The analysis helps generate meaningful insights into global energy consumption and environmental impact.

## Objectives
- Analyze total emissions by country for the most recent available year.
- Identify the top five countries by GDP.
- Compare energy production and consumption across countries and years.
- Identify energy types contributing most to emissions.
- Analyze changes in global emissions and GDP over time.
- Calculate energy consumption and production per capita.
- Examine emission-to-GDP and consumption-to-GDP ratios.
- Compare countries based on population, emissions, and energy usage.
- Generate data-driven insights to understand global energy patterns.

## Tools and Technologies
- MySQL
- SQL
- Relational Database Management
- Data Analysis

## Database Schema
The project uses a MySQL database named `ENERGYDB2`, containing six related tables:

1. **country** – Stores country identifiers and country names.
2. **emission_3** – Contains energy types, emissions, years, and per-capita emissions.
3. **population** – Stores population values by country and year.
4. **production** – Contains energy production data by country, energy type, and year.
5. **gdp_3** – Stores GDP values by country and year.
6. **consumption** – Contains energy consumption data by country, energy type, and year.

Primary and foreign key relationships connect the tables for relational analysis.

## SQL Concepts Used
- CREATE DATABASE and CREATE TABLE
- Primary Keys and Foreign Keys
- SELECT and WHERE
- GROUP BY and ORDER BY
- Aggregate Functions such as SUM() and AVG()
- JOIN operations
- Subqueries
- LIMIT
- NULLIF() for handling zero denominators
- Data aggregation and trend analysis

## Key Analysis and Insights
The project investigates 18 analytical questions covering comparative analysis, trends, ratios, per-capita metrics, and global comparisons.

Examples of insights documented in the project presentation:
- China has the highest emissions in the latest-year comparison shown.
- China and the United States lead the GDP ranking in the displayed results.
- Global emissions increased from 67,852 in 2020 to 74,161 in 2023.
- CO₂ emissions are the largest emission category in the displayed analysis.
- China contributes the largest share of global emissions in the presentation.
- Population, GDP, energy production, and emissions are compared across countries and years.

These findings reflect the results documented in the project presentation and depend on the dataset and query definitions.

## Project Workflow
1. Created the ENERGYDB2 database.
2. Designed six related tables.
3. Established relationships using primary and foreign keys.
4. Formulated business and analytical questions.
5. Wrote SQL queries using joins, aggregations, and subqueries.
6. Compared country-level and global metrics.
7. Interpreted the query outputs to identify trends and insights.

## Repository Structure
```
Energy-Consumption-Analysis/
├── README.md
├── ENERGY CONSUMPTION ANALYSIS.sql
└── SQL PROJECT.pptx
```

## Skills Demonstrated
- SQL querying and data analysis
- Relational database design
- Data aggregation and comparison
- Trend analysis
- Working with multiple related tables
- Translating business questions into SQL queries
- Drawing insights from structured data

## Conclusion
This project provided practical experience in using MySQL to analyze energy production, consumption, emissions, GDP, and population data. It strengthened my understanding of relational databases, SQL joins, aggregate functions, subqueries, and analytical problem-solving.

The project demonstrates how SQL can be used to explore complex datasets and generate insights that support a better understanding of global energy trends and environmental impact.

## Author
**VedaSree**

GitHub: [nagavedasreethota012-lgtm](https://github.com/nagavedasreethota012-lgtm)

LinkedIn: [Thota Naga Vedasree](https://www.linkedin.com/in/naga-vedasree-thota-056388279/)
