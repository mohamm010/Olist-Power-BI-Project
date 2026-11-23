# Olist Brazilian E-Commerce Analytics

An end-to-end **Business Intelligence project** built with Microsoft Power BI to analyze e-commerce sales performance, product performance, delivery operations, and customer behavior using the Olist Brazilian E-Commerce dataset.

The project transforms raw e-commerce data into an interactive dashboard that helps explore business performance, identify operational patterns, and uncover potential areas for improvement.

## Project Objectives

- Evaluate sales performance and order trends over time.
- Analyze product and category contributions to sales.
- Assess delivery performance, delays, and shipping costs.
- Understand customer purchasing behavior through RFM-based segmentation.
- Explore customer reviews and factors associated with customer experience.
- Forecast future sales value, order volume, and average order value.

## Tools & Technologies

- **Microsoft Power BI:** Data modeling, analysis, and visualization.
- **Power Query:** Data cleaning and transformation.
- **DAX:** Measures and analytical calculations.
- **SQL Server:** Data storage and connectivity.
- **CSV:** Source data files.

## Data Source

**Olist Brazilian E-Commerce Dataset**

A publicly available dataset containing information about orders, products, customers, sellers, payments, shipping, and customer reviews.

Source: [Olist Brazilian E-Commerce Dataset – Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## Project Workflow

1. **Data Integration:** Connected to data stored in SQL Server and CSV files.
2. **Data Preparation:** Cleaned and transformed datasets using Power Query, including handling missing values, standardizing categories, and validating data quality.
3. **Data Modeling:** Built a relational data model connecting fact tables, dimensions, and supporting analytical tables.
4. **Data Analysis:** Developed DAX measures to evaluate sales, orders, delivery operations, and customer experience.
5. **Dashboard Development:** Created interactive reports with KPIs, charts, comparisons, geographical analysis, and forecasting.

## Dashboard Structure

The report consists of five interactive analytical pages:

### 1. Overview

Provides a high-level summary of business performance through key metrics, including total orders, sales value, average order value, and distinct customers.

### 2. Sales & Products

Explores sales trends, monthly performance, product category contributions, shipping impact, and payment methods.

### 3. Delivery Performance

Evaluates delivery efficiency through delivery duration, delays, on-time delivery rates, and geographical comparisons.

### 4. Customer Experience

Analyzes customer ratings, review distributions, customer segments, and relationships between delivery performance and customer ratings.

### 5. Forecasting

Uses Power BI's built-in forecasting capabilities to explore future trends in:

- Monthly Sales Value
- Monthly Order Count
- Monthly Average Order Value

Forecasts include confidence intervals to communicate the uncertainty associated with projected values.

## Analytical Highlights

- Analyzed **93,358 unique customers** using RFM-related metrics.
- Identified three customer segments: One-Time Customers, High-Value Customers, and Repeat Customers.
- Found that One-Time Customers represent the largest segment, with 73,420 customers.
- Identified 197 unusual order records through delivery-date validation and isolated them for quality review without removing them from the main dataset.
- Connected operational indicators with customer ratings to explore patterns associated with customer experience.

## Limitations & Considerations

- The analysis is based on the historical data available in the Olist dataset.
- Actual net profit cannot be calculated because complete cost information is unavailable.
- Customer segmentation thresholds are specific to this dataset and should not be treated as universal benchmarks.
- Geographical coordinates represent approximate postal-code locations rather than exact addresses.
- Forecasts are statistical estimates based on historical patterns, not guaranteed future outcomes.
- Customer reviews are analyzed through numerical ratings and comment availability; no independent NLP or sentiment analysis model was implemented.

## Project Outcome

The final deliverable is an interactive Power BI dashboard that integrates commercial, operational, and customer-related analysis into a unified reporting experience.

It demonstrates the use of data preparation, relational data modeling, DAX calculations, business analysis, and data visualization to turn raw e-commerce data into actionable business insights.
