# Executive Sales & Profitability Dashboard

An interactive Power BI dashboard built to analyse Superstore sales performance, profitability, regional differences, customer segments, and product performance. The project turns raw retail transaction data into insights that can help management make informed business decisions.

## Project Overview

The goal of this project is to understand what drives the Superstore's sales and profitability, identify areas that need improvement, and provide practical recommendations based on the data.

Using Power Query for data cleaning and preparation and Power BI for analysis and visualisation, the project explores overall business performance and highlights opportunities to improve profitability and support business growth.

## Dataset Summary

- **Source:** [Kaggle – Superstore Dataset Final](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Original records:** 9,994 rows
- **Records after cleaning:** 9,993 rows
- **Duplicate records removed:** 1 exact duplicate
- **Missing values:** None identified during the data quality check

### Key Attributes

The dataset includes the following fields:

- **Order and customer details:** `Order ID`, `Customer Name`, `Segment`
- **Geographical information:** `Country`, `Region`, `State`, `City`, `Postal Code`
- **Product information:** `Product ID`, `Product Name`, `Category`, `Sub-Category`
- **Sales metrics:** `Sales`, `Quantity`, `Discount`, `Profit`

## Data Cleaning and Preparation

Data extraction, cleaning, and transformation were carried out in **Power Query** before loading the data into Power BI.

### 1. Column Review

Removed the `Row ID` column because it served as a row identifier and was not required for the planned analysis.

### 2. Duplicate Removal

Checked the dataset for exact duplicate records across all columns and removed one duplicate row associated with Order ID `US-2014-150119`. The duplicate had identical values across all fields, including customer, segment, and product details.

### 3. Data Quality Checks

Used column profiling to check for missing and null values. No missing or null values were identified in the dataset during this check.

### 4. Data Type Standardisation

Reviewed and standardised data types to support accurate calculations, filtering, and aggregation in Power BI.


## Key Business Questions

The dashboard was developed to answer the following questions:

1. **Overall performance:** What are the company's total sales, total profit, and overall profit margin?
2. **Regional performance:** Which regions generate the highest sales and profit, and where are profit margins lower?
3. **Customer segments:** Which customer segments contribute the most revenue?
4. **Product performance:** Which product categories perform best, and which individual products generate the highest profits or profit margins?
5. **Sales trends:** How does sales performance change over time, and what patterns can be observed throughout the year?
6. **Management recommendations:** What actions can management take to improve profitability, strengthen sales performance, and allocate resources more effectively?

## Key Metrics and Analysis

The dashboard brings together key performance indicators and visualisations to help users explore the company's performance, including:

- Total sales
- Total profit
- Overall profit margin
- Sales contribution by customer segment
- Sales and profitability by region
- Product and category performance
- Monthly sales trends

## Tools Used

- **Power BI:** Dashboard development, data modelling, and visualisation.
- **Power Query:** Data cleaning, transformation, and preparation.
- **DAX:** Measures and calculations for business performance analysis.

