# Online Retail Sales Analysis

## Project Overview

This project explores historical online retail transaction data to evaluate sales performance, identify product and geographical revenue patterns, and understand customer purchasing behaviour.

Using Python for data preparation and exploratory data analysis, alongside Power BI for interactive visualisation, the project transforms raw transaction records into actionable business insights.

The analysis covers transactions recorded between December 2010 and December 2011.

## Business Objectives

The primary objectives of this analysis were to:

- Evaluate overall sales performance using key business metrics.
- Identify revenue trends and changes in monthly sales performance.
- Examine product performance based on revenue and quantity sold.
- Analyse geographical revenue distribution across countries.
- Understand customer purchasing behaviour and repeat customer contribution.
- Develop data-driven recommendations to support business decisions.

## Tools and Technologies

| Tool | Application |
|---|---|
| Python | Data preparation and exploratory data analysis |
| Pandas | Data manipulation, cleaning and aggregation |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Power BI | Interactive dashboards and business reporting |
| Jupyter Notebook | Analysis environment |

## Dataset Description

The project uses the Online Retail dataset obtained from Kaggle.

The original dataset contains 536,641 transaction records covering the period from December 2010 to December 2011.

Key fields include:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

Additional analytical features were created during data preparation, including:

- Revenue
- TransactionType
- DayOfWeek
- Hour

Following data preparation and transaction filtering, the final sales dataset contained 524,878 records.

**Note:** December 2011 contains only partial-month data, ending on 9 December 2011.

## Data Preparation

Python and Pandas were used to inspect, clean and prepare the transaction data.

Key preparation activities included:

1. Inspecting dataset structure, data types and missing values.
2. Reviewing missing customer identifiers and data quality.
3. Classifying transactions into sales, cancellations/returns and other transaction categories.
4. Filtering sales transactions for the main revenue analysis.
5. Creating additional analytical features, including Revenue, DayOfWeek and Hour.
6. Excluding non-product descriptions from product-level analysis where appropriate.
7. Standardising stock-code casing when combining code variations for product analysis.

The final sales dataset was used for the main sales performance calculations.

## Key Performance Indicators

The analysis produced the following results:

| Metric | Result |
|---|---:|
| Total Sales Revenue | £10,642,110.80 |
| Total Orders | 19,960 |
| Identified Customers | 4,338 |
| Units Sold | 5,572,420 |
| Average Order Value | £533.17 |

*Revenue represents the value of sales transactions included in the analysis. It should not be interpreted as profit.*

## Key Findings

### 1. Sales Performance

- Total sales revenue reached approximately £10.64 million.
- The analysis recorded 19,960 orders.
- November 2011 generated the highest monthly revenue at approximately £1.50 million.
- Revenue increased significantly between September and November 2011.

### 2. Geographical Performance

- The United Kingdom generated approximately £9.00 million in revenue.
- This represented approximately 84.6% of total sales revenue.
- The results indicate a substantial concentration of revenue in the UK market.

### 3. Customer Behaviour

- The dataset contained 4,338 customers with identifiable customer IDs.
- 2,845 customers made repeat purchases.
- Repeat customers contributed approximately £8.27 million in revenue.
- One-time customers contributed approximately £613,989.56.

Customer analysis is based on identifiable customer records; transactions with missing customer IDs cannot be reliably assigned to individual customers.

### 4. Product Performance

Product performance was examined using both revenue and quantity sold.

The analysis identified differences between products generating high revenue and those selling in high volumes, demonstrating why both measures are important when evaluating product performance.

## Power BI Dashboard

An interactive Power BI dashboard was developed to communicate the findings through visual reporting.

The dashboard includes:

<img width="893" height="576" alt="Screenshot (229)" src="https://github.com/user-attachments/assets/cbb16d57-1919-471b-9c7c-4b1807d2c2ad" />


The dashboard provides a visual overview of the business performance and supports exploration of the key analytical findings.

## Business Recommendations

Based on the findings, the following recommendations were identified:

1. **Market diversification:** Explore opportunities to increase sales in other countries to reduce dependence on the UK market.
2. **Customer retention:** Strengthen customer retention initiatives by understanding the purchasing patterns of repeat customers.
3. **Product strategy:** Evaluate products using both revenue and quantity sold when making inventory and merchandising decisions.
4. **Sales monitoring:** Monitor monthly revenue trends to identify periods of strong and weak performance.
5. **Further investigation:** Investigate unusually large transactions and high-value orders to understand their contribution to overall sales.

## Project Limitations

- The dataset covers a historical period rather than current retail activity.
- December 2011 contains incomplete monthly data.
- Some customer records have missing CustomerID values.
- The dataset does not contain sufficient cost information to calculate profit margins.
- Findings describe historical transaction patterns and should not automatically be treated as predictions of future performance.

## Project Deliverables

The repository contains the analytical work and reporting materials associated with the project.

- Python analysis notebook
- Cleaned sales dataset
- Power BI dashboard
- Project presentation

## Conclusion

This project demonstrates the application of Python and Power BI to a real-world-style retail analytics problem.

Through data preparation, exploratory analysis, visualisation and business interpretation, the project identifies key revenue patterns, product performance differences, geographical concentration and customer purchasing behaviour.

It demonstrates the process of transforming raw transactional data into meaningful business insights that can support informed decision-making.

---

**Project Type:** Independent Data Analytics Portfolio Project  
**Tools:** Python, Pandas, Matplotlib and Power BI  
**Dataset:** Online Retail – Kaggle
