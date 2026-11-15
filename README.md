# Retail Sales Analytics Dashboard | Power BI

## Project Overview
This project analyses retail sales data using Microsoft Power BI. The objective is to understand sales performance, product trends, store performance, customer behaviour, and product returns through interactive dashboards.

## Business Objectives
- Analyse overall sales performance.
- Identify top-performing product categories and brands.
- Compare sales across stores and regions.
- Understand customer purchasing patterns.
- Analyse product returns and return reasons.
- Track key performance indicators (KPIs).

## Dataset
The project uses the following tables:

| Table | Description |
|---|---|
| Sales | Transaction-level sales data |
| Products | Product details and categories |
| Customers | Customer information |
| Stores | Store and regional information |
| Returns | Product return records |

## Data Cleaning and Preparation
Data preparation was performed using Power Query.

- Removed duplicate sales records.
- Handled missing PaymentMethod values.
- Standardised SalesChannel values.
- Checked data types and data consistency.
- Validated relationships between fact and dimension tables.
- Retained and reviewed exceptional records such as zero-quantity sales.

## Data Modelling
Created a relational data model using fact and dimension tables.

- Sales
- Returns
- Products
- Customers
- Stores
- Date Table
- Return Date Table

## DAX and Analysis
Created DAX measures to calculate:

- Total Net Sales
- Total Orders
- Total Units Sold
- Average Order Value
- Total Customers
- Total Returns
- Returned Units
- Return Rate %
- Month-over-Month Growth
- Year-over-Year Growth
- Year-to-Date Sales

## Dashboard Pages

### 1. Executive Overview
Provides an overview of sales KPIs, monthly sales trends, category performance, and regional performance.

### 2. Product & Store Analysis
Compares product categories, brands, stores, and regional sales performance.

### 3. Customer & Returns Analysis
Analyses customer performance, return volume, return reasons, and return rate.

### 4. Product Details
Provides detailed product-level analysis through drill-through functionality.

### 5. Store Tooltip
Displays additional store performance metrics through report tooltips.

## Key Business Insights

- Electronics was the highest-performing product category, generating approximately ₹1.16 crore in sales.
- North Kerala was the highest-performing store region, generating approximately ₹68.27 lakh.
- Wrong Item was the most common return reason, with 25 returns.
- Changed Mind was the least common return reason, with 10 returns.
- The reported return rate was 4.54%, calculated using returned units divided by total units sold.
- Chennai was the highest-performing store, with approximately ₹35.8 lakh in sales.

*Note: Figures should be validated against the final Power BI report before publication.*

## Project Limitations
- Profitability could not be analysed because product cost data was not available.
- Return Rate represents returned units as a percentage of total units sold, not the percentage of orders returned.

## Tools & Technologies
- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Modelling
- Data Visualization

## Conclusion
This project demonstrates practical skills in data cleaning, data modelling, DAX calculations, interactive dashboard development, and business insight generation using Power BI.
