# NovaCart Sales Data Analytics Project

## Project Overview

This project focuses on cleaning, transforming, organizing, and analyzing NovaCart sales data using Microsoft Excel and Power BI.

The objective is to improve data quality, prepare structured datasets, and support sales performance analysis through business intelligence and data visualization.

## Tools & Technologies

- **Microsoft Excel:** Data cleaning, transformation, formulas, and PivotTables
- **Power BI:** Data modeling, analysis, and dashboard development
- **CSV:** Raw dataset storage
- **GitHub:** Project documentation and version control

## Dataset Description

The NovaCart dataset contains information about customer transactions, products, orders, sales channels, pricing, discounts, and returns.

The dataset was organized into three primary tables:

**Customer Data**
- Customer ID
- Customer Full Name
- First Name and Last Name
- Email Address
- Customer Segment

**Product Data**
- Product ID
- Product Name
- Product Category

**Order Data**
- Order Date and Order ID
- Customer ID and Product ID
- Sales Channel
- Quantity and Unit Price
- Discount Percentage
- Line Total
- Returned Status

## Data Cleaning Process

### 1. Data Quality Assessment

- Identified missing values, blank cells, and potential duplicates.
- Checked formatting inconsistencies.
- Created a separate CALC worksheet for data analysis.

### 2. Handling Missing Values

Used statistical methods to identify suitable replacement values:

| Metric | Calculated Value |
|---|---|
| Mode of Order ID | 1044 |
| Mode of Quantity | 1 |
| Average Unit Price | 38.84 |
| Average Discount | 5.5 |
| Mode of Returned | 0 |

Missing product names were filled using the most frequently occurring product within each category.

### 3. Data Transformation

- Separated customer, product, and order information into individual worksheets.
- Used lookup functions to retrieve related records.
- Standardized customer information.
- Formatted dates and currency values.
- Calculated line totals using quantity, unit price, and discount percentage.

### 4. Excel Functions Used

`UNIQUE` `SORT` `FILTER` `XLOOKUP` `VLOOKUP` `IF` `MODE` `AVERAGE` `TEXTBEFORE` `TEXTAFTER` `LOWER` `CONCATENATE`

Additional features included PivotTables, filtering, and number formatting.

## Power BI Analysis

The Power BI project file is included in this repository for further exploration of the NovaCart sales dataset.

Power BI supports analysis of sales performance, product categories, customer segments, sales channels, discounts, and returns.

## Project Files

- **Novacart_Dataset.csv:** Source dataset
- **Novacart.xlsx:** Excel workbook used for data cleaning and preparation
- **Novacart.pbix:** Power BI project
- **NOVACART DATA CLEANING.pdf:** Documentation of the cleaning methodology

## Skills Demonstrated

- Data Cleaning and Data Preparation
- Excel Formulas and Lookup Functions
- Data Quality Assessment
- Data Transformation
- Data Organization
- Business Intelligence
- Sales Data Analysis
- Power BI

## Author

**Roopika**

Data Analytics | Microsoft Excel | Power BI
