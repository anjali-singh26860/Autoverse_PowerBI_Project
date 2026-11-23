# AUTOVERSE – Automotive Dealership Sales & Customer Insights

An interactive Power BI dashboard project designed to analyse automotive dealership sales, vehicle performance, customer behaviour, and financing patterns.

## Project Overview

AUTOVERSE is a business intelligence project built using Microsoft Power BI. It transforms raw car-sales data into interactive dashboards to support sales performance monitoring and business decision-making.

## Project Objectives

- Analyse overall automotive sales performance.
- Compare vehicle brands, models, and segments.
- Understand customer demographics and buying behaviour.
- Analyse financing methods and EMI tenure.
- Evaluate dealership regional performance.
- Monitor discounts, selling prices, and delivery waiting times.

## Dataset Information

| Attribute | Details |
|---|---|
| Dataset | CarSales_Data_Raw.csv |
| Records | 200 |
| Original Columns | 22 |
| Period | January 2019 – December 2024 |
| Currency | INR (₹) |
| Geographic Scope | India – dealership regions |

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel
- CSV Data Sources

## Data Cleaning & Preparation

The dataset was prepared using Power Query.

Key activities included:

- Text trimming and cleaning.
- Standardising transmission and fuel categories.
- Normalising finance types and vehicle segments.
- Cleaning mixed-format currency and numeric columns.
- Standardising Yes/No/Unknown values.
- Converting mixed-format dates into valid dates.
- Checking missing values and duplicate records.
- Validating sales prices and discount amounts.

## Dashboard Pages

### 01 – Executive Sales Overview

- Net Sales Value
- Cars Sold
- Average Selling Price
- Total Discounts
- Discount Percentage
- Monthly Net Sales Trend
- Sales by Brand
- Cars Sold by Region
- Vehicle Segment Distribution

### 02 – Vehicle & Product Performance

- Brands Available
- Models Available
- Average Selling Price
- Average Discount
- Average Customer Rating
- Brand Sales Comparison
- Average Selling Price by Brand
- Top 10 Car Models
- Fuel Type Performance

### 03 – Customer & Finance Insights

- Average Customer Rating
- Rating Responses
- Average Waiting Days
- Repeat Buyer Percentage
- Test Drive Percentage
- Customer Gender Distribution
- Finance Type Distribution
- EMI Tenure Analysis
- Dealership Performance by Region
- Average Waiting Days by Brand

## Key Business Metrics

| KPI | Result |
|---|---:|
| Cars Sold | 200 |
| Gross Sales | ₹400.70 Million |
| Net Sales Value | ₹392.47 Million |
| Total Discounts | ₹8.23 Million |
| Average Selling Price | ₹1.96 Million |
| Discount Percentage | 2.05% |
| Average Customer Rating | 4.22 |
| Repeat Buyer Percentage | 54.00% |
| Test Drive Percentage | 50.50% |

*These figures represent the supplied dataset sample and are not industry-wide market estimates.*

## Data Quality Notes & Limitations

- The dataset contains 200 sales records.
- 40 customer-rating records were missing or marked NA.
- 24 EMI tenure records were missing.
- 20 waiting-time records were missing.
- The dataset does not contain a salesperson identifier, so salesperson-level rankings are not included.
- The findings should be interpreted within the scope of this sample dataset.

## Project Structure

- `01_Raw_Data` – Original dataset
- `02_Cleaned_Data` – Cleaned dataset
- `03_PowerBI_File` – Power BI project file
- `04_Assets` – Dashboard graphics and car visuals
- Final_Exports` – Dashboard screenshots and exported reports

## Project Author

Created as a Power BI business intelligence and data analytics portfolio project.

**Project:** AUTOVERSE – Automotive Dealership Sales & Customer Insights

**GitHub:** https://github.com/anjali-singh26860/Autoverse_PowerBI_Project
