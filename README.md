# Late Shipment Prediction in an E-Commerce


## Description

> Late shipment prediction using machine learning algorithm

## Dataset

> https://www.kaggle.com/prachi13/customer-analytics

## Outline

- Data Extraction
- Exploratory Data Analysis
- Data Preparation
- Model Evaluation
- Churned Customer and Potential Gross Profit Calculation


## Objective

> Create a system to help predict and calculate late shipment automatically


## Summary of Findings

- The algorithm that has the best performance (83%) in evaluating the results of this prediction is K-nearest Neighbor with hyperparameter tuning using grid search
- It is probably influenced by non-linear data
- From of all the algorithms carried out, the majority of the top-5 features are::
    - Discount offered
    - Weight in gms
    - Cost of the product
    - Prior purchases
    - Customer rating

- From the evaluation of prediction result, we can calculate number of occurence of late shipment by performance is 83%
- Based on performance, the percentage of churned customers will decrease by 8,466%
- The prediction for the possible profit that will be obtained from running the model and implementing the recommendations is IDR 3 billion.
- Evaluating features that affect to the arrival time would help to recommend and handle the factors affecting late shipment
- Since the feature that influences the most is the 'discount offered', if analysed, logically if an e-commerce company gives a lot of discounts, there will be many transactions. Of course this will affect the increasing number of product shipments on couriers or shipping expeditions which cause overload and delay in delivery. Therefore, we recommend to add shipping options, especially for Express Delivery (1 Day), and additional workers to support the new shipping options.

