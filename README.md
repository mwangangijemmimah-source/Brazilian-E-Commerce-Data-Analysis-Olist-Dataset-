# Brazilian-E-Commerce-Data-Analysis-Olist-Dataset-
Python ,Pandas ,Visualization, Merging and Filtering.
Project Overview

This repository contains a comprehensive data cleaning and exploratory data analysis (EDA) of the Brazilian E-Commerce Public Dataset by Olist. The project focuses on transforming raw transactional data into actionable business insights using Python and the Pandas library.

The analysis covers a wide range of data analyses workflows, including:

•
Relational Data Merging: Joining 9 distinct tables to reconstruct the full customer journey.

•
Data Cleaning: Handling missing values, parsing timestamps, and resolving logical duplicates in geolocation data.

•
Business Intelligence: Calculating KPIs like customer retention, revenue growth, and delivery performance.

•
Data Visualization: Using Pandas and Matplotlib to visualize trends, distributions, and market shares.




Dataset Structure

The dataset consists of 100k orders from 2016 to 2018, spread across multiple tables:

•
olist_customers_dataset.csv: Customer information and location.

•
olist_orders_dataset.csv: Order status, timestamps, and delivery tracking.

•
olist_order_items_dataset.csv: Product details, pricing, and freight per order.

•
olist_order_payments_dataset.csv: Payment methods and installment details.

•
olist_products_dataset.csv: Product dimensions and categories.

•
olist_sellers_dataset.csv: Seller locations.

•
product_category_name_translation.csv: Portuguese to English category mapping.




Key Analysis Questions

The project is structured around 10 core questions that test different aspects of data manipulation:

Part 1: Calculation-Based Insights

1.
Customer Loyalty: Identifying unique customers and calculating the repeat purchase rate.

2.
Data Integrity: Assessing the impact of missing delivery dates on the dataset.

3.
Logistics Analysis: Determining the heaviest product categories by average weight.

4.
Financial Patterns: Identifying the most common payment methods for high-installment purchases.

5.
Local Commerce: Calculating the percentage of orders fulfilled by sellers in the same state as the customer.

6.
Customer Satisfaction: Comparing review scores between on-time and late deliveries.

Part 2: Visual Explorations

1.
Sales Volume: A horizontal bar chart of the Top 10 product categories by items sold.

2.
Payment Share: A pie chart showing the market share of different payment types (Credit Card, Boleto, etc.).

3.
Operational Efficiency: A histogram showing the distribution of order approval times.

4.
Growth Trends: A time-series line plot tracking monthly revenue growth from 2016 to 2018.




Key Findings

•
Delivery Impact: Late deliveries significantly hurt customer satisfaction, with average review scores dropping from 4.29 (on-time) to 2.57 (late).

•
Payment Dominance: Credit cards account for 78.4% of the total transaction value on the platform.

•
Growth: The platform experienced explosive revenue growth throughout 2017, peaking during the Black Friday period in November.

•
Retention: Only about 3% of customers made repeat purchases during the timeframe of the dataset, indicating a high customer acquisition focus.

