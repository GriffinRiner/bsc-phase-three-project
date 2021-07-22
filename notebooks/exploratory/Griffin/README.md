# This folder should contain all exploratory notebooks for member-1

# Telco Customer Data
 briefly covers your process, methodology and findings.

    Take the time to make sure that you craft your story well, and clearly explain your process and findings in a way that shows both your technical expertise and your ability to communicate your results!
    Begin with framing questions, describe your data source, include relevant, well labeled visualizations that support your conclusions, which come at the end.
 
## Overview
The focus of this project was to predict if a customer will churn and to find out what the likelihood of that is for each customer. The analysis of this company has allowed for a model to be made to predict churn of the customers and the likelihood along with recommendation to the business to reduce this likelihood. This model can be used by Telco to make better informed decisions on where to allocate customer retention resources and reduce losses in revenue from lost customers.
 
## Business Problem
Telco would like to be able to predict whether a customer has a high likelihood of dropping their services and which customers they need to spend more resources on to keep and which ones require the most resources to retain.

## Data
The data was collected from a Kaggle dataset titled "Telco Customer Churn". It has 21 columns of customer data that is used to predict customer churn. This data was used to create a model to predict if a customer will churn and the percent risk they are to churn. This data was also used to feature engineer new columns that would be more useful for prediction. The data was used to create informative visuals.

### Source
The columns used for prediction were Gender (gender of the customer), SeniorCitizen (whether the customer is a senior citizen), Partner (whether the customer is married), Dependents (whether the customer has children), Tenure (the number of months the customer has been with the company), PhoneService (whether the customer uses the company for phone service), MultipleLines (whether the customer has multiple phone lines), InternetService (whether the customer uses the company for internet service), OnlineSecurity (whether the customer uses the online security service), OnlineBackup (whether the customer uses the online backup service), DeviceProtection (whether the customer uses the device protection service), TechSupport (whether the customer uses the tech support service), StreamingTV (whether the customer uses the TV streaming service), StreamingMovies (whether the customer uses the movie streaming service), Contract (whether the customer is on a month-to-month, one year, or two year contract), PayperlessBilling (whether the customer uses payperless billing), PaymentMethod (whether the customer pays by electronic check, mailed check, automatic bank transfer, or credit card), MonthlyCharges (The amount the customer is charged each month), TotalCharges (the total amount the customer has been charged), and Churn (whether the customer has discontinued use of the company in the past month (the target variable)).

Engineered features include totchg_per_tenure (the amount of the total charge divided by the customer's tenure), monthly_div_tot (the customer's monthly charges divided by their total charges), single_parent (if the customer has a dependent but does not have a partner), phone_and_internet (if the customer uses the company for phone and internet service), num_of_internet_services (the number of additional internet services the customer uses), and num_of_services (the number of total additional services the customer uses).
    
## Process
eda
impute, scale, encode
choosing a scoring metric
modeling process
scoring

## Findings
final model 
visuals of all models
why chosen
interpretability
feature import
precision quantiles
some graphs
recommendations