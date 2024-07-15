# Adidas Sales Analysis
This project is a comprehensive exploratory data analysis (EDA) of Adidas sales data. The analysis aims to understand the sales performance, retailer and product distribution, sales methods, and various other metrics to derive meaningful insights.

### Table of Contents
- Introduction
- Libraries Used
- Data Description
- Data Cleaning
- Data Analysis
- Visualizations
- Conclusions
- How to Run

## Introduction
This project focuses on analyzing Adidas sales data to extract insights regarding sales performance across different products, retailers, and sales methods. The analysis includes data cleaning, checking for null and duplicate values, and various visualizations to better understand the data.

## Libraries Used
The following libraries are used in this analysis:
- numpy
- pandas
- matplotlib
- seaborn
- plotly

## Data Description
The dataset used in this analysis includes the following columns:
- Invoice Date
- Retailer
- Product
- Sales Method
- Units Sold
- Price per Unit
- Total Sales
- Operating Margin
- Operating Profit

## Data Cleaning
Several steps were taken to clean and prepare the data for analysis:

1. Converted the Invoice Date column to datetime format.
2. Checked for duplicate and null values.
3. Ensured numeric data correctness by recalculating Total Sales and Operating Profit.

## Data Analysis
The analysis includes:

1. Counting the number of unique retailers and products.
2. Analyzing the distribution of sales methods.
3. Checking the date range of the data.
4. Exploring the cities involved in sales.

## Visualizations
Various visualizations were created to illustrate the insights:

1. Retailer Distribution: Boxplot showing the distribution of retailers.
2. Sales Methods: Bar chart showing total sales by sales method.
3. Product Sales by Method: Heatmap showing product sales across different methods.
4. Sales by Date: Line chart showing sales over time.
5. City-wise Operating Profit: Bar chart showing operating profit by city.

## Conclusions
The analysis provides insights into the sales performance of Adidas products, highlighting key metrics such as the most profitable sales methods, top-performing retailers, and the distribution of sales across different cities.

## How to Run
To run the analysis, follow these steps:

1. Ensure you have the required libraries installed:
> pip install numpy pandas matplotlib seaborn plotly
2. Load the Jupyter notebook and run each cell sequentially to reproduce the analysis and visualizations.
