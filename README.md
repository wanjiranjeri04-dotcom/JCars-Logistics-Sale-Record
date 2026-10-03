# JCars Logistics Power BI Business Intelligence Project

## Project Overview

This project focuses on analysing JCars Logistics vehicle sales data using Power BI. The aim was to transform raw and inconsistent data into a clean, structured dataset and an interactive dashboard that provides useful business insights.

## Objectives

- Clean and standardise the raw JCars dataset
- Identify and address data quality issues
- Transform and validate the data
- Create a structured data model using fact and dimension tables
- Develop DAX measures for key business metrics
- Build an interactive Power BI dashboard
- Analyse sales,revenue,profitability,customers,vehicles,regions and sales representatives

## Data Preparation

The raw dataset contained issues such as inconsistent formats, missing values, duplicate or unusual entries, inconsistent categories, and different formats for dates and numerical values.

The data was cleaned and transformed using Power Query before being used for analysis.

Key areas of data preparation included:

- Cleaning and standardising text fields
- Handling missing and invalid values
- Standardising dates
- Converting numerical and monetary fields
- Standardising categories such as customer type, vehicle type, region, and payment methods
- Validating calculated values
- Creating relationships between fact and dimension tables

## Data Model

The Power BI model was organised using a fact and dimension structure.

### Fact Table
- Fact_table

### Dimension Tables
- Dim_Customer
- Dim_SalesRep
- Dim_Location
- Dim_Vehicles
- Dim_Date

This structure was used to make the data easier to analyse and improve the performance of the Power BI report.

## Dashboard

The final dashboard provides an executive overview of JCars' performance.

It includes:

- Total Revenue
- Total Cars Sold
- Total Sales
- Gross Profit
- Gross Margin
- Revenue by Sales Representative
- Revenue and Gross Profit by Vehicle Type
- Revenue by Customer Type
- Revenue by Region

Interactive slicers allow users to analyse the data by:

- Customer Type
- Order Date
- Region
- Sales Representative
- Vehicle Type

## Tools Used

- Power Query
- Microsoft Power BI
- DAX
- Git & GitHub

## Key Learning

This project provided practical experience in taking a raw dataset through the full data analytics process:

**Raw Data → Cleaning → Transformation → Data Modelling → DAX → Visualisation → Business Insights**

It also helped strengthen my understanding of how data quality and proper data modelling affect the accuracy and usefulness of business analysis.

## Project Files

- `data/` – cleaned dataset
- Power BI report – interactive dashboard
- `screenshots/` – dashboard and project screenshots

## Conclusion

The project demonstrates how Power BI can be used to transform raw vehicle sales data into an interactive business intelligence solution that makes key business information easier to understand and analyse.
