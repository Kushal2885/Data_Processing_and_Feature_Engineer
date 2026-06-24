# Customer Purchase Behavior Analysis and Data Profiling

## Project Overview

This project focuses on Data Preprocessing, Data Acquisition, Data Cleaning, Exploratory Data Analysis (EDA), and Data Profiling using a customer purchase behavior dataset.

The objective is to understand customer purchasing patterns and prepare the dataset for machine learning applications such as Customer Churn Prediction.

---

## Objective

The primary goal of this project is to:

* Collect data from multiple sources.
* Perform data cleaning and preprocessing.
* Conduct Exploratory Data Analysis (EDA).
* Generate automated data profiling reports.
* Understand customer purchase behavior.
* Prepare the dataset for machine learning tasks.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SQLite
* Requests API
* YData Profiling
* Jupyter Notebook

---

## Dataset Information

The dataset contains customer purchase behavior information with the following attributes:

| Column                | Description                   |
| --------------------- | ----------------------------- |
| CustomerID            | Unique customer identifier    |
| Age                   | Customer age                  |
| Gender                | Male/Female                   |
| AnnualIncome          | Annual income of customer     |
| PurchaseFrequency     | Number of purchases made      |
| AveragePurchaseAmount | Average spending per purchase |
| LastPurchaseDays      | Days since last purchase      |
| Churn                 | Customer churn status         |

---

## Part A: Fundamentals

### Topics Covered

* What is Data Analysis?
* Data Science Project Lifecycle
* Machine Learning Problem Statement
* Introduction to Tensors
* Tensor Examples using NumPy

---

## Part B: Data Acquisition

Data was collected from multiple sources:

### SQL Database

* Created a SQLite database (`customers.db`)
* Created customer table
* Inserted customer records
* Retrieved data using SQL queries

### CSV File

* Exported SQL data into CSV format
* Loaded CSV using Pandas

### JSON File

* Converted CSV data into JSON format
* Parsed JSON using Pandas

### API Data

* Retrieved user data from Random User API
* Processed JSON response using Pandas

---

## Part C: Data Understanding and Cleaning

The following preprocessing techniques were applied:

* Dataset exploration using `head()`
* Data inspection using `info()`
* Statistical summary using `describe()`
* Missing value analysis
* Data type verification
* Duplicate record checking
* Data quality validation

---

## Part D: Exploratory Data Analysis (EDA)

### Univariate Analysis

* Age Distribution
* Annual Income Distribution
* Average Purchase Amount Distribution

### Bivariate Analysis

* Gender vs Purchase Amount
* Income vs Churn
* Annual Income Distribution by Churn

### Multivariate Analysis

* Correlation Heatmap
* Pair Plot Analysis

### Key Insights

* Customers with higher income tend to purchase more frequently.
* Purchase behavior varies across customer groups.
* Certain variables show strong correlation with customer spending patterns.
* Churn behavior can be analyzed using demographic and purchase-related features.

---

## Part E: Data Profiling

A comprehensive profiling report was generated using the YData Profiling library.

The report includes:

* Missing Value Analysis
* Descriptive Statistics
* Correlation Analysis
* Data Quality Warnings
* Variable Distributions

---

## Machine Learning Problem

### Customer Churn Prediction

The project aims to predict whether a customer is likely to churn based on:

* Age
* Income
* Purchase Frequency
* Purchase Amount
* Purchase History

Target Variable:

* Yes → Customer will churn
* No → Customer will not churn

---

## Project Structure

```text
Data_Profiler.ipynb
customers.db
customers.csv
customers.json
customer_profile_report.html
README.md
```

---

## Conclusion

This project successfully demonstrates the complete data analysis workflow, including data acquisition, preprocessing, exploratory data analysis, and automated profiling. The prepared dataset can be further used for machine learning models such as Customer Churn Prediction and Customer Segmentation.
