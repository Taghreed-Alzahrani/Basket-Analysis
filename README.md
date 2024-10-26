# Basket-Analysis
project Title: E-commerce Basket Analysis 

Authors: 
Taghreed Alzahrani
Jori Bajahnoun

Date: 26/10/2024

Overview:
This project analyzes e-commerce transaction data to discover association rules among purchased items using the Apriori algorithm. The analysis aims to identify frequently bought items together, which can help businesses in product placement, marketing strategies, and inventory management.

Included Files:
Basket_Analysis_task.ipynb: A notebook containing Python.
market_Report.pdf: A report about the task.
filtered_association_rules1.csv: after running the code here are the filtered rules to in a CSV file

Dataset:
This dataset contains transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based non-store online retailer that primarily sells unique all-occasion gifts. Many customers are wholesalers.


How to Install and Run the Project:
Prerequisites
Python: Version 3.6 or higher
Jupyter Notebook, Google Colab or any Python IDE

Installation Steps:
Install Required Libraries: Use pip to install necessary libraries.
pip install pandas matplotlib seaborn mlxtend

Download the Dataset: Obtain the dataset from kaggle (https://www.kaggle.com/datasets/carrie1/ecommerce-data).
Save the dataset as data.csv in the project directory.

Open the Project:
Jupyter Notebook: Open the notebook file.
Python IDE: Open your preferred Python IDE, Create a new Python file and copy the provided code into it.

Run the Code: Execute each cell sequentially to perform the following:
Load and preprocess the dataset.
Create a binary basket representation of purchases.
Apply the Apriori algorithm to find frequent itemsets.
Generate association rules based on specified metrics (confidence and lift).
Filter and save the rules to a CSV file.
