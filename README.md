# Sales and Customer Data Store Analysis

# OVERVIEW
The Sales and Customer Data Store provide one with sales and customer data from Kaggle datasets. The dataset includes the performance of categories between 2021 and 2023. With the help of the analysis, I compared the various categories and sales performance of the Business duration. Based on this comparison, actionable insights were made to see how perfomance could be improved and how category fared during the duration of Business.

# OBJECTIVE 
-Analyze the provided dataset and provide a dashboard for the stakeholders.
-Analyze the sales trend through the Business years?
-Identify interesting trends/outliers/developments and derive actionable insights for the stakeholders.

# TOOLS (SQL & Looker Studio)

1.DATA ACQUISITION
The data source is from Kaggle. Link to three csv:(https://www.kaggle.com/datasets/dataceo/sales-and-customer-data?select=customer_data.csv)

# Metadata: Table Description
i.  Sales_data Table: Containing seven(7) columns:

-Invoice_no: A unique code associated with a invoice transaction.
-Customer_id: A unique ID of each customer.
-Category: The various categories sold within the shop.
-Quantity: Number of quantities bought.
-Price: Price of each quantity.
-Invoice_date: The date each purchase was made.
-Shopping_mall: Various shopping malls purchases were made.


ii. Customer_data Table: Containing four(4) columns:

-customer_id: A unique customer id associated with each customer.
-Gender: gender of each customer.
-Age: various ages of each customer.
-Payment_method: medium through payments were made.

2.DATA EXPLORATION
Data exploration to have an overview of the dataset are done in Bigquery using SQL.
Sales_data and Customer_data were joined to have twelve columns.


-customer_id: A unique customer id associated with each other customer.
-order_id: A unique code associated with a invoice transaction.
-category: The various categories sold within the shop.
-Quantity: Number of quantities bought.
-Price: Price of each quantity.
-toal_Due: Price against quantity bought.
-Invoice_date: The date each purchase was made.
-order_year: The year each purchase was made.
-Shopping_mall: Various shopping malls purchases were made.
-gender: gender of each customer
-Age: various ages of each customer.
-Payment_method: medium through payments were made.

3.DATA CLEANING
Data was cleaned to remove duplicates and null values to reduce 
inconsistencies.


4. DATA TRANSFORMATION
Data was extracted, transformed and loaded into Looker studio for modeling and visualiaztion.
(https://lookerstudio.google.com/u/0/reporting/4eb66efe-ded1-447e-a5f9-eb8c47578dda/page/u6JtD/edit)














