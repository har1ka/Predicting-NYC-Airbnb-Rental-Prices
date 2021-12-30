# Predicting-NYC-Airbnb-Rental-Prices
## Introduction
Our goal is to develop a reliable price prediction model using a range of machine learning methods like Decision Trees, Gradient Boosting, Gradient Boosted Decision Trees and Deep Learning given minimal information about the Airbnb property to aid both the hosts and the customers.

## Why is it interesting?
Since there are many rich features that impact the price of houses, it is fascinating to visualize their patterns/trends, shortlist them, and make reliable predictions using machine learning. Especially for new hosts, it is a challenge to determine the prices and attract customers. And, the existing hosts could increase the listing price, provided the customer base is retained and the pricing is rational. The customer compares the price across similar listings to know the worth of the current price. Accounting for all such different scenarios in a popular city like NYC is a challenge we are trying to solve.

## Process Flow
Simple regression techniques may not serve our purpose of creating a robust model. Since there could be a lot of non-linearity in the data especially with the features, it would be good to execute complex machine learning models. Furthermore, it would be wise to use Decision Trees as they account for non-linearity in the data along with Deep Neural Networks. We are aiming to suggest models that could account for all. 

During the initial preprocessing, we studied each feature of the dataset to treat missing fields, changed the data types accordingly and encoded the categorical features. In the Exploratory Data Analysis, we checked the distribution of each feature, the value counts of the categorical features and the relation between the independent variables and the response. Through feature engineering, we have calculated a few new features that can be fed into modeling. We have trained multiple machine learning models like Decision Trees, Random Forests, Gradient Boosting Trees and a 2-layer, 3-layer Neural Networks on the final dataset split in the ratio 80:20. Then, their predictions are evaluated based on Mean Absolute Error and Mean Squared Error.


