# Black-Friday-Sales-Prediction

![image](https://user-images.githubusercontent.com/58620359/174943679-b5ea9daf-c9bc-43e1-8c35-78292bba62bc.png)

[Link](https://datahack.analyticsvidhya.com/contest/black-friday/) to the contest

## Problem Statement/Objective:

This is Black Friday shopping dataset, from which a retail company “ABC Private Limited” wants to understand the customer purchase behaviour (specifically, purchase amount) against various products of different categories. They have shared purchase summary of various customers for selected high volume products from last month. The data set also contains customer demographics (age, gender, marital status, city_type, stay_in_current_city), product details (product_id and product category) and purchase_amount.Such predictor has a clear commercial value to the store owners as it would help with their financial planning, inventory management, marketing, and advertising.

## Dataset Description

This dataset comprises of sales transactions captured at a retail store. It’s a classic dataset to explore and expand your feature engineering skills and day to day understanding from multiple shopping experiences. This is a regression problem, the idea and dataset is taken from AnalyticsVidhya where the project is a part of a hackathon.

There are two datasets provided Train and Test; I will be using Train dataset for training using train-test split and the test dataset will be used as an input (set of independent variables) to predict the output (dependent variable -Purchase Amount)

* Shape of training set: (550068 records and 12 features)

* Shape of test set: (233599 records and 11 features)

### Various features:

1. User_ID : User ID
2. Product_ID : Product ID
3. Gender : Sex of User
4. Age : Age in bins
5. Occupation : Occupation (Masked)
6. City_Category : Category of the City (A,B,C)
7. Stay_In_Current_City_Years: Number of years stay in current city
8. Marital_Status: Marital Status
9. Product_Category_1: Product Category (Masked)
10. Product_Category_2 : Product may belongs to other category also (Masked)
11. Product_Category_3: Product may belongs to other category also (Masked)
12. Purchase : Purchase Amount (Target Variable)
