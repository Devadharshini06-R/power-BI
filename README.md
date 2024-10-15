**Sales and Profit Analysis for Chocolate Products**

This Power BI project provides an in-depth analysis of sales, shipment, and profit metrics for a chocolate product company. The dashboard is designed to give users a clear understanding of the company's performance over time, enabling data-driven decision-making.

Project Overview

The project is a comprehensive sales analysis that leverages Power BI's data modeling, visualization, and DAX capabilities. The analysis focuses on key metrics like sales revenue, profit margins, shipment performance, and product category breakdowns, with dynamic visualizations and interactive features.

Features
Sales Performance Analysis: Visualizations showcasing total sales, profit, and quantity sold across time periods.

Shipment Analysis: Tracking shipment efficiency and related costs.

Profitability Metrics: Insights into profit margins by product category, region, and sales channel.

Interactive Dashboards: Dynamic filters and slicers for real-time data exploration (by region, product type, time, etc.).

Time Intelligence: Advanced DAX calculations for year-over-year comparisons and month-on-month trends.

Custom Visualizations: Histograms, gauge charts, and line charts for performance monitoring.
Key Metrics

Sales: Total sales amount for the selected period.

Profit: Profit margins at different granularity levels (region, product category, etc.).

Shipment Efficiency: Performance metrics related to shipping times and costs.

LBS%: Weight-related metrics for better inventory management.

Data Sources
The data used for this analysis is a mock dataset representing sales and shipment data for chocolate products. 

Key dimensions include:

Date: Time period (Year, Quarter, Month, Day)

Region: Sales by region

Product Category: Breakdown by product type (chocolate bars, assorted chocolates, etc.)

Sales Channel: Different channels through which the product was sold

Shipment: Shipment and logistics-related metrics


DAX Functions
This project makes use of several advanced DAX functions to deliver meaningful insights, including:

CALCULATE: To create time-based calculations.

SUMX: For dynamic aggregation of sales and profit values.

DATEADD: To track month-on-month and year-on-year performance.

RANKX: For ranking regions and product categories by sales and profit.

Visualization Types

Dynamic Histograms: For product-wise distribution of sales and profits.

Gauge Charts: For tracking profit and shipment targets.

Line Charts: To display sales trends over time.

Bar and Column Charts: Comparative analysis of product categories and regions.
Installation and Setup

Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/Devadharshini06-R/sales-and-profit-analysis-for-chocolate-products.git
Open the .pbix file in Power BI Desktop.

Review the data model and explore the dashboards.
How to Use

Open the Power BI dashboard.
Use the slicers on the right side to filter data by time period, product category, region, or sales channel.
Hover over visuals to get detailed tooltip insights.
Navigate between pages for different analysis sections (Sales Overview, Shipment Analysis, Profit Breakdown).

Future Enhancements

Predictive Analysis: Adding forecasting for future sales and profit trends.

Geographical Maps: Incorporating more advanced location-based analytics.

More Custom Visualizations: Enhancing the dashboard with additional custom visuals for deeper insights.


