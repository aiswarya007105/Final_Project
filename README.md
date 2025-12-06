# Final_Project
# Sales Data Analysis

## Overview

This repository contains a Jupyter Notebook (`sales_analysis_full.ipynb`) that performs a comprehensive analysis of a sales dataset. The objective of this analysis is to derive insights into sales performance, customer behavior, and operational efficiencies to facilitate data-driven decision-making.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset Description](#dataset-description)
3. [Steps Included](#steps-included)
4. [Requirements](#requirements)
5. [How to Run](#how-to-run)
6. [Key Insights](#key-insights)
7. [Additional Resources](#additional-resources)

## Introduction

The main objective of this analysis is to explore the sales data, identify key trends, and provide actionable recommendations that can enhance business strategies and improve sales performance.

## Dataset Description

The dataset consists of various attributes related to sales transactions, including:

- **Order_ID**: Unique identifier for each order.
- **Order_Date**: Date when the order was placed.
- **Ship_Date**: Date when the order was shipped.
- **Customer_ID**: Unique identifier for each customer.
- **Customer_Name**: Name of the customer.
- **Product_ID**: Unique identifier for each product sold.
- **Product_Name**: Name of the product.
- **Product_Category**: Category of the product (e.g., Electronics, Furniture).
- **Quantity**: Number of units sold.
- **Unit_Price**: Price per unit of the product.
- **Sales**: Total sales amount (Quantity × Unit_Price).
- **Discount**: Discount percentage applied to the order.
- **Profit**: Profit earned from the sale.
- **Region**: Geographical region where the sale occurred.
- **Ship_Mode**: Shipping method used for the order.

## Steps Included

1. **Data Loading & Overview**: 
   - Load the dataset using Pandas.
   - Provide a summary of dimensions (rows and columns) and data types.
   - Display initial observations using methods like `head()`, `info()`, and `describe()`.

2. **Data Cleaning & Preprocessing**: 
   - Address missing values, remove duplicates, and convert data types for consistency.

3. **Feature Engineering**: 
   - Create new features to enhance the analysis, such as extracting year and month from order dates and calculating profit margins.

4. **Exploratory Data Analysis (EDA)**: 
   - Generate twelve insightful plots to visualize data trends, including sales distributions, time series analysis, and category performance.

5. **Key Insights & Recommendations**: 
   - Summarize key findings and provide actionable insights based on the visual analysis.

## Requirements

To run this notebook, the following packages need to be installed in your Python environment:

- Python 3.x
- Pandas
- NumPy
- Matplotlib

You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib

#How to Run
Clone this repository:

bash
git clone <repository_url>

Navigate to the directory containing the notebook:

bash
cd <directory_name>

Open Jupyter Notebook:

bash
jupyter notebook

Open the sales_analysis_full.ipynb file and run the cells in sequence to perform the analysis.
