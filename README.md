# Customer-Sales-Data-Analysis-and-Forecasting


## Overview
This repository contains Python scripts for analyzing customer sales data and forecasting future sales trends. The analysis covers various aspects such as sales quantity, revenue, and product performance, while the forecasting uses linear regression and Prophet models to predict future sales.

## Features
- **Data Cleaning and Preparation**: Includes steps to clean and preprocess the data, handle missing values, and standardize text fields.
- **Dimension and Fact Tables Creation**: Generates dimension and fact tables for analysis.
- **Sales Analysis**: Answers key business questions such as the year with the lowest quantity sold for photography products, the product line with the highest quantity sold, and more.
- **Forecasting**: Utilizes both Linear Regression and Prophet models to forecast future sales.
- **Visualization**: Provides various visualizations, including revenue vs. planned revenue, quantity sold vs. target sales, and trend analysis over time.

## Installation
To get started, clone this repository and install the required packages. You can use pip to install them:

```bash
pip install matplotlib seaborn statsmodels scikit-learn prophet
```
## Usage 
### Data Preparation
  - Load your customer sales data into a DataFrame.
  - Perform data cleaning, including filling missing values and standardizing text fields.

## Create Dimension and Fact Tables:

  - Generate dimension tables for Date, Product, Customer, and Loyalty.
  - Create a fact table for Sales with foreign keys to the dimension tables.

## Data Analysis:
   - Perform queries to answer business questions related to sales and customer demographics.
   - Use aggregation and filtering to find insights such as the highest and lowest sales.

## Forecasting:
    - Prepare data for forecasting by converting dates and aggregating sales.
    - Train and predict using both Linear Regression and Prophet models.
    - Plot forecasts and analyze trends.

## Visualization
  - Generate various plots to visualize revenue, quantity sold, and percentage achievements.
  - Create detailed line plots for sales trends over time.

## Contributing
Feel free to contribute to this project by opening issues or submitting pull requests. Your feedback and improvements are welcome!
