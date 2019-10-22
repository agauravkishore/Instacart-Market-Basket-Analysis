# Instacart-Market-Basket-Analysis
Predicting if the customer will reorder a particular Item
---------------------------------------------------------


Introduction
----------------------------------------------------
Instacart is an American technology company, Founded in 2012, that operates as a same-day grocery delivery and pick-up service in the U.S. and Canada. It is currently valued at nearly $8 billion. Customers shop for groceries through the Instacart mobile app or Instacart.com from the company's more than 300 national, regional and local retailer partners. The order is shopped and delivered by an Instacart personal shopper

Project Objectives:
----------------------------------------------------

In this project we have used anonymized data on customer orders over time to predict which previously purchased products will be in a user’s next order. The main motivation of this project is to solve the objectives as listed below.
•	predict whether a product will be reordered or not.
•	Predict which department a product will belong to 

Data set:
----------------------------------------------------
In 2017, the company announced its first public dataset release, which is anonymized and contains a sample of over 3 million grocery orders from more than 200,000 Instacart users. 
As a part of the project, we worked on the following six datasets:

Aisles.csv
Department
Order_products_prior.csv
Order_products_train
Orders.csv
Products.csv

You can download these datasets at 
https://www.kaggle.com/c/instacart-market-basket-analysis/data




Data Cleaning
----------------------------------------------------

I checked the data for missing values. The data was relatively clean and only the orders.csv dataset had any missing values. We calculated the length of the entire column and then the number of missing values for each column. The percentage of missing values per columns were then calculated.

No missing values were present in the aisles, deparments, order_product_prior, order_product_train and products databases. The only missing values found were in Orders dataset. Only the orders dataset had any missing values. I observed that, only 6% of days_since_prior_order column in the orders dataset were null. So, I decided to truncate them. This was done to ensure that there are no null values in the dataset.
