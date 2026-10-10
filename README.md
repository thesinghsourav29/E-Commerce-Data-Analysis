# E-Commerce Sales Data Analysis

## Project Overview
An end-to-end data analytics project using Python, Pandas, MySQL, and Power BI to analyze retail transactions, sales performance, customer behavior, country-wise revenue, and product returns.

## Tools & Technologies
- **Python:** Data cleaning and exploratory data analysis
- **Pandas:** Data manipulation and aggregation
- **MySQL:** SQL queries and business analysis
- **Power BI:** Interactive dashboard and KPI reporting

## Dataset
The project uses the Online Retail II dataset, containing invoice-level retail transactions, product details, quantities, prices, customer IDs, dates, and countries.

## Project Workflow
1. Cleaned the raw dataset and removed duplicate records.
2. Handled missing customer IDs while retaining valid transactions for overall sales analysis.
3. Created revenue, transaction-type, and monthly analysis fields.
4. Imported the cleaned dataset into MySQL.
5. Used SQL to analyze revenue, orders, customers, countries, and returns.
6. Built a Power BI dashboard with KPI cards and charts for monthly revenue, country-wise revenue, and sales versus returns.

## Key Findings
- **Total net revenue:** Approximately £9.64 million
- **Sales revenue before returns:** Approximately £10.27 million
- **Returns value:** Approximately £0.63 million
- The United Kingdom contributed the largest share of revenue.
- Monthly revenue peaked in November 2010 within the available data.
- December 2010 is a partial month because the dataset ends on December 9, 2010.

## Project Structure
- `Data/` — Raw and cleaned datasets
- `python/` — Python analysis notebook
- `sql/` — SQL analysis scripts
- `powerbi/` — Power BI dashboard

## Business Value
This project demonstrates practical skills in data cleaning, SQL querying, KPI analysis, customer and market analysis, and business dashboard development.