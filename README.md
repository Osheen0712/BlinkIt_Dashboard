# BlinkIt Power BI Dashboard

## Table of Contents :
  Overview
 - Files
 - How to Use
 - Key Insights and Visuals
 - Conclusion

## Overview
This project involves analyzing the sales and inventory data of BlinkIT Grocery using Microsoft Power BI. The aim is to provide insights into various aspects of the business, such as sales performance, inventory management, customer behavior, and more. The analysis is presented in an interactive dashboard, which allows stakeholders to explore the data and derive meaningful insights.

## Files
  - BlinkIT Grocery Data.xlsx
This Excel file contains the raw data used for analysis. The data includes information on sales, inventory, products, customers, and other relevant metrics.

 - BlinkIt Dashboard.pbix
This Power BI file contains the interactive dashboard created using the data from the Excel file. The dashboard provides visual representations of the data, including charts, graphs, and tables.

# How to Use
 - Prerequisites
  - Microsoft Power BI Desktop installed on your computer.
 - Steps to Access the Dashboard
  - Open the Dashboard:
     - Launch Microsoft Power BI Desktop.
     - Open the BlinkIt Dashboard.pbix file by navigating to File > Open and selecting the file from its location.
 
  - Review Data Connections:
    - Ensure that the data connections in the Power BI file are correctly linked to the BlinkIT Grocery Data.xlsx file. If needed, update the data source by navigating to Home > Transform Data > Data Source Settings and making the necessary changes.

  - Explore the Dashboard:
    - Navigate through the different pages of the dashboard to explore various aspects of the data.
    - Use the interactive features such as filters, slicers, and drill-through options to delve deeper into specific metrics and insights.

# Key Insights and Visuals
 - Sales Performance:
  - Visualizations showing total sales, sales trends over time, and comparisons between different periods.
  - Insights into top-performing products and categories.
  - Measures:
     - Total Sales: Sum of all sales transactions.
     - Average Sales: Average sales value per transaction.

- Inventory Management:
 - Charts displaying inventory levels, stock turnover rates, and inventory aging.
 - Analysis of stockouts and overstock situations.
 - Measures:
    - Number of Items: Total count of unique items in inventory.

- Customer Analysis:
 - Demographic breakdown of customers.
 - Customer purchase patterns and behavior analysis.
 - Measures:
    - Average Rating: Average customer rating for products.

- Operational Efficiency:
 - Metrics related to order fulfillment times, delivery efficiency, and supplier performance.

# Changes in Power Query Editor
- Additional transformations and data cleaning steps were performed to ensure data quality and consistency.
- Creation of new measures for enhanced analysis:
   - Total Sales = SUM('BlinkIT Grocery Data'[Sales])
   - Average Sales = Average('BlinkIT Grocery Data'[Sales])
   - Number of Items = COUNTROWS('BlinkIT Grocery Data')
   - Average Rating = AVERAGE('BlinkIT Grocery Data'[Rating])

# Conclusion
This project provides a comprehensive analysis of BlinkIT Grocery's data through an interactive Power BI dashboard. By following the steps outlined above, stakeholders can access and explore the data to gain valuable insights that can inform business decisions and strategies.
