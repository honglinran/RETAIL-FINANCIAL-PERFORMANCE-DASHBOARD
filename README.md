# Electronic Hardware Sales Performance Analysis Dashboard

## Project Overview

This project presents a Power BI business intelligence dashboard developed for an anonymised electronic hardware company. The client operates in a competitive market as a major technology manufacturers and sells electronic products across different regions, markets, customers, product categories and sales channels.

The purpose of this project was to analyse sales, financial, product and supply chain performance so that business stakeholders could make better data-driven decisions. The dashboard was designed to support senior management, finance teams, sales teams, product managers and supply chain teams by providing clear insights into profitability, customer performance, product performance and forecast accuracy.

The project was completed as part of a consulting-style data analysis project, where the client provided electronic hardware sales data and the analysis team transformed it into meaningful business insights.

---

## Business Context

The client wanted to understand:

- Which regions, markets, customers and products were driving the strongest sales performance
- How profitable the business was after deductions and cost of goods sold
- Which customers and products were performing best or worst
- Whether supply chain forecasting was accurate enough to support inventory planning
- Where the business could reduce risk, improve margin and make better commercial decisions

---

## Key Business Problems Solved

### 1. Financial Performance Analysis

The dashboard provides a Profit and Loss view to help stakeholders understand how revenue moves from gross sales to gross margin.

Key financial concepts included:

- Gross Sales
- Pre-invoice deductions
- Net Invoice Sales
- Post-invoice deductions
- Net Sales
- Cost of Goods Sold
- Gross Margin
- Gross Margin %

This helps the client understand whether the business is generating healthy profit after discounts, deductions and operating costs.

### 2. Top and Bottom Customer Performance

The dashboard identifies high-performing and low-performing customers based on key sales and profitability metrics.

This helps the sales team:

- Prioritise valuable customers
- Identify customers with declining performance
- Support account management decisions
- Understand which customers contribute most to revenue and margin

### 3. Product Sales Performance

The dashboard compares product segments, categories and individual products by net sales, gross margin and quantity sold.

This helps product and commercial teams:

- Identify best-selling product groups
- Understand which products generate strong margin
- Detect underperforming categories
- Support pricing, promotion and product portfolio decisions

### 4. Supply Chain Forecast Accuracy

The supply chain view analyses forecast accuracy, net error and absolute error.

This helps supply chain stakeholders:

- Understand whether demand forecasts are reliable
- Identify products or customers with high forecasting errors
- Detect risks such as out-of-stock or excess inventory
- Improve inventory planning and demand management

---

## Dashboard Pages

### 1. Financial View

The financial view focuses on Profit and Loss performance. It includes:

- Net Sales KPI
- Gross Margin % KPI
- Profit and Loss statement
- Net sales trend over time
- Regional and product-level P&L breakdown
- Top and bottom customers and products by sales performance

### 2. Supply Chain View

The supply chain view focuses on forecast accuracy and demand planning. It includes:

- Forecast Accuracy %
- Net Error
- Absolute Error
- Forecast accuracy by customer
- Forecast accuracy by product segment
- Risk indicators such as out-of-stock and excess inventory
- Monthly forecast performance trend

### 3. Sales View

The sales view focuses on customer and product sales performance. It includes:

- Customer performance table
- Product performance table
- Net Sales
- Gross Margin
- Gross Margin %
- Quantity sold
- Customer and regional performance matrix

### 4. Product / Marketing View

The product and marketing view focuses on product performance by segment, division and region. It includes:

- Product performance by segment and category
- Regional, market and customer performance
- Product-level performance matrix
- Comparison of net sales and gross margin %

### 5. Data Model View

The data model connects multiple fact and dimension tables to support accurate reporting and analysis.

Main tables include:

- `fact_sales_monthly`
- `fact_forecast_monthly`
- `fact_actuals_estimates`
- `dim_customer`
- `dim_product`
- `dim_market`
- `dim_date`
- `manufacturing_cost`
- `freight_cost`
- `gross_price`
- `pre_invoice_deductions`
- `post_invoice_deductions`
- `marketshare`

---

## Tools and Technologies Used

- Power BI
- MySQL
- Power Query
- DAX
- Data Modelling
- Time Intelligence
- Data Cleaning
- Data Transformation
- Business Intelligence Reporting
- Dashboard UX Design

---

## Data Connection and Preparation

The dataset was imported into Power BI from a MySQL database. After importing the data, I cleaned and transformed the tables using Power Query.

The preparation process included:

- Connecting Power BI to a MySQL database
- Importing sales, forecast, customer, product, market and cost tables
- Cleaning and transforming the data in Power Query
- Creating relationships between fact and dimension tables
- Building a structured data model
- Creating DAX measures for financial and sales KPIs
- Applying time intelligence calculations such as YTD, YTG and Landing Estimate
- Designing interactive dashboard pages for different business users

---

## Key Measures Created

Examples of business measures included:

- Net Sales
- Gross Sales
- Net Invoice Sales
- Gross Margin
- Gross Margin %
- Forecast Accuracy %
- Net Error
- Absolute Error
- Year-to-Date Sales
- Year-to-Go Forecast
- Landing Estimate
- Year-on-Year Change
- Year-on-Year Change %

---

## Business Insights

Some key insights from the dashboard include:

- Total Net Sales reached approximately $3.74B in the selected period.
- Total Gross Margin was approximately $1.42B.
- Overall Gross Margin % was approximately 38.08%.
- APAC generated the highest regional net sales, followed by North America and Europe.
- Notebook products generated the highest net sales among product segments.
- Some product segments showed supply chain risk, including out-of-stock and excess inventory issues.
- Forecast accuracy reached around 81.17%, but some customers and product categories still showed high forecast errors.
- The dashboard highlighted both strong revenue opportunities and areas where cost, margin and forecasting needed improvement.

---

## Project Outcome

This dashboard helped transform raw electronic hardware sales data into a clear business intelligence solution. It allowed stakeholders to monitor financial performance, compare products and customers, understand regional trends and identify supply chain risks.

The project improved my ability to think beyond dashboard visuals and focus on real business questions. I developed stronger skills in Power BI, DAX, Power Query, data modelling, financial analysis, stakeholder-focused reporting and dashboard design.

---

## Screenshots

### Financial View

![Financial View](images/financial-view.png)

### Supply Chain View

![Supply Chain View](images/supply-chain-view.png)

### Sales View

![Sales View](images/sales-view.png)

### Product / Marketing View

![Product View](images/product-view.png)

### Data Model

![Data Model](images/data-model.png)

---

## What I Learned

Through this project, I learned how to:

- Build a business-focused Power BI dashboard
- Connect Power BI to a MySQL database
- Design a relational data model
- Use Power Query for data cleaning and transformation
- Create DAX measures for financial and operational KPIs
- Apply business time intelligence concepts such as YTD, YTG and Landing Estimate
- Analyse customer, product, regional and supply chain performance
- Design dashboard pages for different stakeholder needs
- Present insights in a clear and professional way

---

## Confidentiality Notice

This project is based on an anonymised business case and electronic hardware sales dataset. Any company names, customer names or sensitive business information have been removed or replaced for portfolio purposes.
