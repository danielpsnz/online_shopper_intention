# Customer Classification for Online Retail

## Overview
As data scientists working for a retail company, we are tasked with enhancing the online sales service due to shifting consumer habits. To achieve this, we aim to develop a machine learning model to classify customers based on the probability of generating revenue through online purchases. The objective is to tailor specific actions for customers who are more likely to make purchases on the website.

The company has been gathering data using Google Analytics, providing session data for individual customers over a one-year period.

## Project Tasks
The following tasks have been outlined by the company:

* Data Analysis: Conduct exploratory data analysis on the Google Analytics dataset, including histograms, box plots, and other relevant analyses with a clear business interpretation.
* Data Preprocessing:
** Handle missing values, outliers, etc., if present, using appropriate methods such as Pandas' dropna().
** Process categorical variables by converting them into numerical values through techniques like one-hot encoding, mapping, or label encoding, providing justifications for the chosen operations.
** Delete any unnecessary variables with justification if required.
* Data Standardization: Standardize the data.
* Data Splitting: Divide the data into training and testing sets. Train models using CrossValidation and GridSearch with the training data.
* Model Building:
** Utilize a linear model such as logistic regression or linear regression.
** Implement a neural network model.
** Employ any other classification model.
* Model Optimization: Optimize model parameters using CrossValidation and GridSearch or other suitable methods, providing justifications.
* Model Evaluation: Select the best model among the three based on ROC metric in CrossValidation. Predict on the test set and obtain an estimated metric.
* Probability Thresholding: Adjust probabilities using the threshold maximizing the area under the ROC curve.

## Data Information
The dataset comprises ten numerical attributes and eight categorical attributes. Key features include:

* Revenue: Can be used as the class label.
* Page Views and Durations: Represent the number of pages visited and time spent on different page categories.
* Bounce Rate, Exit Rate, and Page Value: Metrics measured by Google Analytics for each page, indicating visitor behavior and page importance.
* Special Day: Indicates proximity to specific special days, affecting the likelihood of transactions.
* Visitor Information: Includes attributes such as operating system, browser, region, traffic type, visitor type, weekend visit indicator, and month of the year.
