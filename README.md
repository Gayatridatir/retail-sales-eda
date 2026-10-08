# Retail Sales EDA

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset using Python. The goal is to identify sales patterns, customer behaviour, product-category performance, and actionable business insights.

## Objective

The main objectives of this project are:

* Inspect and understand the retail sales dataset
* Calculate descriptive statistics
* Analyze monthly and quarterly sales trends
* Analyze customer age groups and gender distribution
* Analyze product-category performance
* Study relationships between numerical variables
* Identify useful business insights
* Provide actionable business recommendations

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Dataset

The dataset contains 1,000 retail transactions with the following information:

* Transaction ID
* Date
* Customer ID
* Gender
* Age
* Product Category
* Quantity
* Price per Unit
* Total Amount

## Analysis Performed

### 1. Dataset Inspection

Checked the dataset shape, column names, data types, missing values, and duplicate records.

### 2. Descriptive Statistics

Calculated:

* Mean
* Median
* Mode
* Standard deviation

for numerical variables.

### 3. Monthly Sales Trend

Analyzed monthly sales using a line chart to identify changes in sales performance throughout the year.

### 4. Quarterly Sales Trend

Analyzed quarterly sales to understand broader sales performance across the year.

### 5. Customer Demographics

Analyzed:

* Customer age groups
* Gender distribution

to understand the customer base.

### 6. Product Category Analysis

Analyzed revenue and quantity sold by product category.

> Note: The dataset contains product categories but does not contain individual product names. Therefore, product-level analysis was performed at the product-category level.

### 7. Correlation Analysis

Created a correlation heatmap to study relationships between numerical variables such as:

* Age
* Quantity
* Price per Unit
* Total Amount

### 8. Additional Analysis

Analyzed average transaction spending across different customer age groups to identify potential high-value customer segments.

## Key Business Insights

The analysis helps identify:

* Monthly and quarterly sales patterns
* Major customer age groups
* Gender distribution
* High-performing product categories
* Customer spending behaviour
* Relationships between numerical variables

## Business Recommendations

### 1. Improve Inventory Planning

Maintain sufficient stock for high-demand product categories to reduce the risk of stock shortages.

### 2. Use Targeted Marketing

Create targeted marketing campaigns based on customer demographics such as age groups and gender.

### 3. Plan Seasonal Promotions

Use monthly and quarterly sales trends to plan promotional campaigns during low-sales periods and maximize opportunities during high-sales periods.

### 4. Focus on High-Revenue Categories

Give appropriate inventory and marketing attention to product categories generating higher revenue.

### 5. Identify High-Value Customers

Use average spending analysis to identify customer segments with higher transaction values and develop suitable loyalty or promotional strategies.

## Project Structure

```text
Retail-Sales-EDA/
│
├── Task_1_Retail_Sales_EDA.ipynb
├── README.md
└── requirements.txt
```

## Conclusion

The exploratory data analysis provides useful insights into retail sales trends, customer demographics, product-category performance, and customer spending behaviour. These insights can support data-driven decisions related to inventory management, marketing, promotions, and revenue growth.
