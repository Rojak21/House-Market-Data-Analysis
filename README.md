# Home Market Overview

An interactive Power BI dashboard developed to analyze housing market sales, pricing trends, regional performance, and sales growth.

## Tools & Technologies

* Power BI
* BigQuery
* DAX
* Power Query

## Data Source

The housing dataset was loaded into **Google BigQuery** and connected to Power BI for analysis and visualization. This project also provided hands-on experience working with BigQuery as a cloud data source.

The dataset contains information such as:

* Transaction date and fiscal quarter
* House ID and house type
* Sales type — New or Resale
* Year built
* Offer price and purchase price
* Price change percentage
* Number of rooms
* House area in square meters
* Price per square meter
* Region and property address

## Dashboard Pages

### 1. Home Market Overview

This page provides an overall view of housing market trends.

**Visuals used:**

* Median Sales Price Change by Region — Bar Chart
* Key market metrics — Cards
* Offer Price vs Purchase Price — Scatter Chart
* YOY Sales Growth by Sales Type — Line Chart

### 2. Sales Performance

This page focuses on sales and regional performance.

**Visuals used:**

* Sales by Region — Bar Chart
* Purchase Price analysis — Key Influencers
* Date-wise Purchase Price and Total Sales — Table
* Offer-to-SQM Ratio by Sales Type — Bar Chart
* Average Price per SQM by Region — Donut Chart

## DAX Measures

Created a dedicated **Measures table** to keep all calculations organized.

Key measures include:

* Average Price per SQM
* Last 12 Months Sales
* Median Sales Price Change
* Offer-to-SQM Ratio
* Sales by Region
* Total YTD Sales
* Units Sold in Latest Year and Quarter
* YOY Sales Growth

These measures were used to calculate sales trends, compare current and previous-year performance, analyze regional sales, and evaluate housing prices.

## Key Learning
Through this project, I gained practical experience in connecting **BigQuery with Power BI**, creating DAX measures, analyzing housing sales data, and building interactive dashboards to identify pricing and sales trends.
