# Fashion E-commerce Analytics

This project focuses on data analysis for a simulated digital fashion store operation in Europe, emphasizing e-commerce and mobile app channels.

## About

The fashion industry is dynamic and competitive, driven by seasonality and multiple sales channels. This project replicates real challenges faced by data analysts in digital fashion companies, providing strategic insights to support decisions on inventory, sales, campaigns, and customer retention.

## Dataset

I created a multitable dataset simulating the store’s full operation, containing information about products, sales, customers, stock, campaigns, and sales channels.  
This dataset has been made available to the community on Kaggle for anyone to use and explore:  
[European Fashion Store Multitable Dataset - Kaggle](https://www.kaggle.com/datasets/joycemara/european-fashion-store-multitable-dataset)

## Objectives

- Monitor sales performance by product, category, channel, and country  
- Identify products with low sales volume or recent declines  
- Detect customers at risk of churn based on inactivity  
- Evaluate the impact of promotional campaigns  
- Manage inventory and identify potential deadstock  

## Technologies

- Python (pandas, pandasql) for SQL-based analysis on DataFrames  
- CSV files representing multiple data sources  

## Key Analyses

- Monthly sales summary (volume, revenue, average ticket)  
- Customers inactive for more than 90 days  
- Ranking of top valuable customers (LTV)  
- Products below average sales and underperforming categories  
- Detection of recent sales drops by product  
- Products in stock without recent sales (possible deadstock)  

## Usage

Ideal for data analysts and managers looking to build monitoring models and support decision-making in digital retail.
