# Customer Shopping Behaviour Analysis

## Overview

This project analyzes customer shopping behaviour using Python, PostgreSQL, Power BI, and reporting tools. The main goal of the project is to understand customer purchase patterns, clean and prepare the data, run SQL-based analysis, and create an interactive dashboard for business insights.

The project follows a complete data analytics workflow, starting from loading the dataset in Python, performing exploratory data analysis, cleaning the data, storing it in a PostgreSQL database, building a Power BI dashboard, and finally preparing a report and presentation.

## Dataset

The dataset used in this project is a customer shopping behaviour dataset. It contains information related to customer demographics, purchase details, product categories, review ratings, discounts, payment methods, and shopping frequency.

Key columns include:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Review Rating
- Subscription Status
- Discount Applied
- Payment Method
- Frequency of Purchases

## Tools and Technologies Used

- Python
- Pandas
- PostgreSQL
- SQLAlchemy
- Psycopg2
- Power BI
- Gamma
- Jupyter Notebook

## Project Steps

### 1. Data Loading

The dataset was loaded into Python using Pandas. The first few records, column details, data types, and summary statistics were checked to understand the structure of the dataset.

### 2. Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the dataset and identify important patterns. This included checking the shape of the data, reviewing column information, checking missing values, and analyzing customer demographics and purchase behaviour.

### 3. Data Cleaning

The dataset was cleaned and prepared for analysis. Missing values were handled, column names were standardized, and unnecessary columns were removed. The review rating column was cleaned by filling missing values using the median rating based on product category.

### 4. Feature Engineering

New columns were created to make the dataset more useful for analysis. An age group column was created to categorize customers into different age ranges. A purchase frequency days column was also created by converting text-based purchase frequency values into numeric day values.

### 5. PostgreSQL Integration

After cleaning the dataset, the data was loaded into a PostgreSQL database. This allowed SQL queries to be run directly on the cleaned data. The cleaned data was stored in a table named customer.

### 6. SQL Analysis

SQL queries were executed on the PostgreSQL server to analyze the data and extract insights. The analysis focused on customer behaviour, category-wise sales, purchase amount trends, age group analysis, discount usage, review ratings, and purchase frequency.

### 7. Power BI Dashboard

A Power BI dashboard was created to visually present the key findings from the analysis. The dashboard included charts, KPIs, and visual summaries to make the insights easy to understand.

### 8. Report and Presentation

A final report was created to explain the full project workflow, analysis, and findings. A presentation was also created using Gamma to present the project in a professional and structured way.

## Dashboard Results

The Power BI dashboard helped identify important customer shopping trends, including:

- Product categories with higher purchase amounts
- Customer distribution by age group
- Gender-based shopping behaviour
- Review rating trends across categories
- Discount usage and its relationship with purchases
- Customer shopping frequency patterns
- Overall sales and purchase behaviour

These insights can help businesses understand their customers better and make better decisions related to marketing, pricing, and product strategy.

