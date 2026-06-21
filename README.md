# Google Merchandise Store Product Analytics Dashboard

## Project Overview

This project demonstrates an end-to-end Product Analytics workflow using Python and Power BI.

The goal was to transform raw ecommerce event data into a business-ready analytics dashboard focused on user behavior, conversion funnel performance, revenue analysis, and product insights.

## Business Questions

* How many users interact with the store?
* How does revenue change over time?
* Where do users drop off in the conversion funnel?
* Which categories generate the most revenue?
* Which products perform best?
* How is revenue distributed across devices?
* What does the customer LTV distribution look like?

## Dataset

Source:
Google Merchandise Sales Data

https://www.kaggle.com/datasets/mexwell/google-merchandise-sales-data

Period:
2020-11-01 — 2021-01-31

## Data Preparation

Performed in Python (Jupyter Notebook):

* Data quality audit
* Datetime conversion
* Dataset joins
* Feature engineering
* Daily revenue calculations
* DAU calculations
* Funnel metrics
* LTV segmentation

## Final Analytical Table

fact_product_analytics

Rows:
758,884

Columns:
17

## Key Metrics

Revenue:
307,114 USD

Users:
14,701

Sessions:
18,034

Purchases:
15,555

Average Order Value:
19.74 USD

## Conversion Funnel

User Conversion:

Add To Cart → Checkout:
51.0%

Checkout → Purchase:
63.5%

Add To Cart → Purchase:
32.4%

## Dashboard Pages

### Executive Overview

Includes:

* Revenue KPI
* Users KPI
* Sessions KPI
* Purchases KPI
* Revenue Trend
* DAU Trend
* Conversion Funnel
* Device Split

### Product Performance

Includes:

* Revenue by Category
* Revenue by Country
* Revenue by Device
* Top Products
* LTV Distribution

## Tech Stack

* Power BI
* Python
* Pandas
* Jupyter Notebook
* SQL
* GitHub

## Repository Structure

data/
notebooks/
dashboard/
screenshots/
exports/

## Screenshots

<img width="1290" height="725" alt="executive_overview" src="https://github.com/user-attachments/assets/c03de389-2f45-492a-8296-df6aaef547c9" />
<img width="1294" height="724" alt="product_performance" src="https://github.com/user-attachments/assets/89630a26-d292-41d7-b0f9-5cbe457684c0" />


## Author

Data / BI Analyst Portfolio Project
