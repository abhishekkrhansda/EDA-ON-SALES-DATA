# 📊 Sales Data EDA

![Python](https://img.shields.io/badge/python-3.9-blue)
![Pandas](https://img.shields.io/badge/pandas-1.5.3-brightgreen)
![Matplotlib](https://img.shields.io/badge/matplotlib-3.7.1-orange)

This notebook performs a **comprehensive Exploratory Data Analysis (EDA)** on the *"Practice EDA on Sales Dataset"* from [Kaggle](https://www.kaggle.com/datasets/dhruvkothari19/practice-eda-on-this-sales-dataset).  
The analysis cleans, preprocesses, and explores sales data to extract actionable business insights.

---

## **Key Steps in the Analysis**

### **1. Data Cleaning**
- Handling null values and removing rows with missing data.
- Removing duplicate entries caused by repeated orders or identical transactions.
- Converting `Order ID`, `Quantity Ordered`, and `Price Each` to numeric types.
- Transforming `Order Date` to `datetime` format for time-based analysis.

### **2. Feature Engineering**
- Extracted `City` and `State` from `Purchase Address`.
- Created `Total Price` column: `Quantity Ordered * Price Each`.
- Extracted `Month`, `Date`, and `Time` from `Order Date`.

### **3. Sales Analysis**
- Identified **best month** for sales.
- Analyzed **city-wise sales** and popular products in each city.
- Determined **top-selling products** and monthly trends.
- Found **optimal time to advertise** based on order times.

### **4. Visualizations**
- Line plots and bar charts to show monthly sales trends.
- Best and worst-selling products each month.
- City-wise sales distribution.
- Quantity of products sold over time.

---

## **Dataset**
- Source: [Kaggle – Practice EDA on Sales Dataset](https://www.kaggle.com/datasets/dhruvkothari19/practice-eda-on-this-sales-dataset)
- Format: CSV files
- Size: ~373,700 rows, 6 columns

---

## **Getting Started**

### **Requirements**
- Python 3.x
- Libraries:
  ```bash
  pandas
  matplotlib
  numpy

