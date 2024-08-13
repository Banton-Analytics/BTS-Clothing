# BTS-Clothing Case Study (Analysis and Visualization) Project

#### Project Objective

This project aims to perform comprehensive data analysis and visualization on BTS Clothing transaction data. By exploring and visualizing key metrics, the project seeks to uncover insights that can drive business decisions, optimize marketing strategies, and improve operational efficiency.

#### Datasets Used

The project utilizes multiple datasets related to BTS transactions:
- Products.csv: Contains product details, including ProductID, Name, Price, and Cost.
- Shipping.csv: Includes shipping information with OrderID, ShippingMethod, and City.
- Stores.csv: Details about store locations, including StoreID and City.
- Transactions.csv: Transaction records including OrderID, ProductID, Quantity, Price, Cost, Date, and additional features like Year, Month, and Day.

#### Methodology

- [X] Data Loading and Cleaning
   - Importing Data: Loaded data from CSV files into Pandas DataFrames for analysis.
   - Handling Missing Values: Filled missing values in key columns such as StoreID and ShippingMethod.
   - Data Type Conversion: Adjusted data types for consistency, including converting columns to appropriate formats.

- [X] Data Transformation
   - Feature Engineering: Created new columns, such as Date (from Year, Month, and Day) and Discount Pct (indicating discounts on specific products).
   - Data Merging: Combined datasets to create comprehensive orders DataFrame through various merges and concatenations.
   - Duplicate Removal: Identified and removed duplicate entries from transaction records.

- [X] Data Analysis
   - Store Metrics: Analyzed performance by store, including metrics like Total Revenue, Total Cost, and order counts.
   - Product Metrics: Evaluated product performance, including Total Revenue and Total Net Profit.
   - Order Metrics: Examined order patterns, including quantities, multi-product orders, and outliers.

- [X] Data Visualization
   - Bar Plots: Visualized quantity sold by ProductID and average discount percentage by City.
   - Scatter Plots: Plotted Total Revenue against Total Cost, highlighting the Total Net Profit.
   - Line Plots: Tracked Total Net Profit over time by Date.
   - Heatmaps: Displayed correlation between key financial metrics.
   - Box Plots: Identified outliers in Total Revenue by product type using Inter Quartile Range.

- [x] Insights and Findings
   - Sales Performance: Identified top-performing products and stores based on Total Revenue and Net Profit.
   - Discount Impact: Analyzed how discounts influenced sales across different cities.
   - Revenue Trends: Revealed trends and patterns in Total Net Profit over time.

#### Conclusion
This project delivered a detailed analysis and visualization of BTS transaction data. The findings provided actionable insights into product performance, store metrics, and sales trends. The visualizations helped in understanding complex data relationships and identifying key areas for further review.

#### Future Work
- Advanced Analytics: Implement predictive models to forecast future sales and revenue.
- Segmentation Analysis: Conduct customer segmentation to tailor marketing strategies.
