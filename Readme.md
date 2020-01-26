# Project Overview

The purpose of this project is to understand and predict customer churn for Sparkify (online music streaming service) by analyzing available online customer journey data and using it in the devleopment of ML solution.

## Problem Statement

Understanding and being able to predict customer churn is highly important for the companies. Knowing, which customer is more likely to Churn, company can react and propose incentives to keep the customer. Customer retention is one of the key areas of marketing. Moreover, retaining customer is usually much cheaper than acquiring a new customer, hence, being able to understand and predict customer churn is crucial for the company to be profitable and successful.

## Metrics

To measure the performance of the churn prediction, f1 score - a harmonized mean of precision and recall will be used as it is important for us not only to accurately predict customers who are about to churn, but also to avoid false positives as we want to avoid providing unnecessary incentives and marketing investment into customers who are not going to churn in reality.

## Definition

Churned customer is a customer who cancels the service subscription

## Data

The data to be analyzed is available on Udacity's workspace. file: mini_sparkify_event_data.json


# Reflection and improvements

An improtant next step here would be to run the same analysis and training/testing/validation on a much larger data set.

To enable the work with a much larger data set, one could use AWS (EC2 instances or Sagemaker)

Additionally, one could look into alternative classification methods and algorithms e.g. famous XGBoost, LightGBM, CatBoost to achieve even better f1 score

For feature generation, one could look into solutions like FeatureTools for automatic deep synthesis and feature generation


# Blog post
The details of the analysis and results are described in the following blog post: https://medium.com/@khodjaev.sh/understanding-and-predicting-customer-churn-with-pyspark-703a30e6eceb