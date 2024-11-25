# RealWorldSalesAnalysis

This repository contains an analysis of real-world sales data aimed at solving business problems. The dataset includes various sales and product details, and the analysis focuses on identifying key trends, insights, and actionable recommendations for maximizing sales and optimizing marketing strategies.

## Project Overview

In this project, we use sales data to address common business questions and generate meaningful insights. The goal is to understand sales trends, customer behavior, and product performance. This can help businesses make data-driven decisions to boost sales and improve customer engagement.

## Data Cleaning

The initial step in this analysis involved data cleaning, which included:
- **Handling missing data**: Identifying and filling or removing any missing or null values.
- **Standardizing date and time formats**: Ensuring that the "Order Date" column was properly formatted for time-based analysis.
- **Removing duplicates**: Identifying and eliminating any duplicate orders to ensure the integrity of the data.
- **Converting data types**: Ensuring correct data types for all columns (e.g., numerical columns for quantities and prices).

## Data Analysis

Once the data was cleaned, we proceeded with the analysis, which was aimed at answering the following business questions:

1. **What are the monthly sales trends?**
   - Analyzing sales data over time to identify seasonal patterns and growth.
   
2. **What city sold the most products?**
   - Identifying top-performing cities based on sales data.
   
3. **What time should we display advertisements to maximize purchases?**
   - Exploring purchase patterns throughout the day to recommend optimal advertising times.
   
4. **What products are most often sold together?**
   - Analyzing product combinations and suggesting cross-selling opportunities.
   
5. **What product sold the most and why?**
   - Identifying top-selling products and analyzing factors like price and sales volume.

## Findings

- **Monthly Sales Trends**: We identified significant seasonal trends, with noticeable peaks in sales during certain months, suggesting a high correlation with holiday seasons and promotions.
  
- **Top Cities by Sales**: Cities like **San Francisco** and **New York** had the highest total sales, which could be attributed to factors like population size, market demand, and local events.

- **Optimal Time for Advertising**: The highest purchase frequency occurred around **11 AM** to **1 PM** and **7 PM** to **9 PM**, suggesting that consumers are more likely to purchase products during lunch breaks and after work hours.

- **Product Combinations**: The most frequently bought product combinations were **'Lightning Charging Cable' and 'iPhone'**, indicating a high level of cross-selling opportunities for complementary products.

- **Most Sold Product**: The **'AA Batteries (4-pack)'** was the most sold product, with a significantly higher quantity ordered than any other product. This could be due to its lower price and high demand in various product categories.


## Data Sources

The dataset used in this project is real-world sales data containing the following key columns:
- **Order ID**: Unique identifier for each order.
- **Product**: The product being sold.
- **Quantity Ordered**: Quantity of the product purchased.
- **Price Each**: Price of the product.
- **Purchase Address**: Customer’s address.
- **Order Date**: Date and time when the order was placed.

## Libraries and Tools Used

- **Python**: The primary programming language for data analysis.
- **Pandas**: Data manipulation and analysis library.
- **Matplotlib & Seaborn**: Visualization libraries for generating charts and graphs.
- **NumPy**: For numerical operations and handling missing data.
- **Counter**: For counting product combinations.
- **Regex**: For data extraction and cleaning.



## Visualizations

Throughout the analysis, visualizations are used to show:
- Monthly sales trends.

![monthly_sales](https://github.com/user-attachments/assets/601eae0e-b285-4abb-b8d1-0202e835358d)
![monthly_sales_treand](https://github.com/user-attachments/assets/c0c37fe3-0fa1-4e59-ad65-1ad5ce9cb1ce)


- The cities with the highest sales.
![quantities_by_cities](https://github.com/user-attachments/assets/1edb7c5f-8934-42d5-9b36-75952f29e4c7)


- The optimal times for advertising based on customer purchasing behavior.



![hours_purchase](https://github.com/user-attachments/assets/670a873a-d44a-4e55-979b-c0045170238e)

![productsales_averageprice](https://github.com/user-attachments/assets/cb1df31d-3d7b-469d-8ced-affc569eed1b)




## Conclusions

Based on the analysis, the following conclusions were drawn:
- **Sales Trends**: Sales vary seasonally and by time of day, suggesting that businesses can optimize their operations and marketing efforts by aligning with these trends.
- **City-Specific Sales**: Certain cities outperform others in total sales, and regional strategies could be designed to cater to these high-performing areas.
- **Cross-Selling Opportunities**: Products that are frequently bought together, like chargers and phones, can be bundled in promotions to increase sales.

## Recommendations

1. **Optimize Marketing and Ads**: Advertise during peak purchasing times (11 AM to 1 PM, 7 PM to 9 PM) to maximize the likelihood of purchases.
2. **Regional Targeting**: Focus marketing efforts on cities with high sales like San Francisco and New York, tailoring promotions to the local demographics.
3. **Promote Product Bundles**: Offer bundles for frequently bought together products, such as combining the **'Lightning Charging Cable'** with the **'iPhone'** to increase sales.
4. **Leverage High-Selling Products**: Products like **AA Batteries** could be featured in promotions, or their availability could be optimized in areas with high demand.
