Sales Data EDA

This notebook performs a comprehensive Exploratory Data Analysis (EDA) on the "Practice EDA on Sales Dataset" from Kaggle. The analysis aims to clean, preprocess, and explore sales data to extract actionable business insights.

Key Steps in the Analysis
1. Data Cleaning

Null Handling: Identified and removed rows with missing values to ensure accurate analysis.

Duplicate Removal: Detected and removed duplicate entries caused by repeated orders or identical transactions.

Data Type Conversion: Converted columns like Order ID, Quantity Ordered, and Price Each to numeric types. Transformed Order Date to datetime format for time-based analysis.

2. Feature Engineering

City & State Extraction: Extracted City and State from the Purchase Address column to analyze location-based sales.

Total Price: Created a Total Price column by multiplying Quantity Ordered with Price Each to calculate revenue per order.

Month, Date & Time Columns: Extracted Month, Date, and Time from the Order Date column to analyze sales trends over time.

3. Sales Analysis

Best Month for Sales: Identified the month with the highest total revenue.

City-wise Sales: Determined which city generated the most sales and which products were most popular in each city.

Top-selling Products: Identified products with the highest quantity sold and analyzed monthly trends.

Optimal Advertising Time: Determined the time of day when most orders are placed, helping to plan marketing campaigns.

4. Visualizations

Line plots and bar charts were used to visualize:

Monthly sales trends

Best and worst-selling products each month

City-wise sales distribution

Quantity of products sold over time
