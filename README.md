# E-commerce Data Mining and Analysis

![](https://www.fasthosts.co.uk/blog/content/images/2020/03/data-mining-large2_03_03_2020.jpg)


## Objective
The goal of this project is to leverage Python and SQL to analyze the E-commerce dataset "Exploring-Ecommerce-database-and-Implementing-Data-Mining". The task involves extracting insights from the data, focusing on customer behavior, product performance, and sales trends.

## Dataset
The dataset consists of various CSV files containing information about orders, products, customers, reviews, payments, and more. The main dataset used in this analysis is `Orders_merged.csv`.

## Setup Instructions

### Clone the Dataset Repository
```bash
git clone https://github.com/mudit-parmar/Exploring-Ecommerce-database-and-Implementing-Data-Mining
```

### Requirements
- Python 3.7+
- Pandas
- Numpy
- SQLite3
- Seaborn
- Matplotlib
- Scikit-learn
- TextBlob

## Data Preparation

### Create Database and Tables
We start by creating an SQLite database to store the data. The following tables are created with appropriate primary and foreign key constraints:
- `customers`
- `product_category`
- `products`
- `sellers`
- `orders`
- `reviews`
- `order_items`
- `order_payments`

### Insert Data into Tables
Data is loaded from the `Orders_merged.csv` file into the database tables. A temporary table `combined` is used to hold the CSV data before inserting it into the structured tables.

## Analysis

### Customer Behavior Analysis
- Identify the top customers by the number of orders and total spend.
- Analyze the geographic distribution of customers.

### Product Performance Analysis
- Identify the top-selling products and categories.
- Analyze the product reviews and ratings to understand customer satisfaction.

### Sales Trends Analysis
- Analyze the sales trends over time to identify peak sales periods.
- Evaluate the effectiveness of different payment methods.

## Conclusion
This project provides a comprehensive analysis of an E-commerce dataset using Python and SQL. The insights derived can help in understanding customer behavior, product performance, and sales trends, which are crucial for making informed business decisions.

For detailed code and analysis, please refer to the `E_commerce_Data_Mining_and_Analysis.ipynb` notebook.
