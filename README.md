# Churny-Jane-Doe
A classification machine learning project to predict the likelihood of a customer leaving the organization.

## Introduction

Customer churn is one of the biggest expenditures of any
organization. Customer churn otherwise known as customer attrition or
customer turnover is the percentage of customers that stopped using your
company\'s product or service within a specified timeframe.\
For instance, if you began the year with 500 customers but later ended
with 480 customers, the percentage of customers that left would be 4%.
If we could figure out why a customer leaves and when they leave with
reasonable accuracy, it would immensely help the organization to
strategize their retention initiatives manifold.

In this project, I aim to find the likelihood of a customer leaving the
organization, the key indicators of churn as well as the retention
strategies that can be implemented to avert this problem.

> Churn Jane Doe is an anonymous identity for any of Telco's customers likely to churn

## What exactly am I doing?
This project is a predictive machine learning problem which leverages on classification algorithm(s) to achieve the business objective at hand.

## What tools do I need?
This is a python project and the various **relevant libraries and modules** needed for this project can be found list in the requirements.txt file within this repository.

## Where are the clues?
The data for this project were derived from three different sources (Microsoft SQL server, GitHub, and OneDrive)  in csv format and are located in *dataset* within this repository. The following describes
the columns present in the data.

**Gender** -- Whether the customer is a male or a female

**SeniorCitizen** -- Whether a customer is a senior citizen or not

**Partner** -- Whether the customer has a partner or not (Yes, No)

**Dependents** -- Whether the customer has dependents or not (Yes, No)

**Tenure** -- Number of months the customer has stayed with the company

**Phone Service** -- Whether the customer has a phone service or not
(Yes, No)

**MultipleLines** -- Whether the customer has multiple lines or not

**InternetService** -- Customer's internet service provider (DSL, Fiber
Optic, No)

**OnlineSecurity** -- Whether the customer has online security or not
(Yes, No, No Internet)

**OnlineBackup** -- Whether the customer has online backup or not (Yes,
No, No Internet)

**DeviceProtection** -- Whether the customer has device protection or
not (Yes, No, No internet service)

**TechSupport** -- Whether the customer has tech support or not (Yes,
No, No internet)

**StreamingTV** -- Whether the customer has streaming TV or not (Yes,
No, No internet service)

**StreamingMovies** -- Whether the customer has streaming movies or not
(Yes, No, No Internet service)

**Contract** -- The contract term of the customer (Month-to-Month, One
year, Two year)

**PaperlessBilling** -- Whether the customer has paperless billing or
not (Yes, No)

**Payment Method** -- The customer's payment method (Electronic check,
mailed check, Bank transfer(automatic), Credit card(automatic))

**MonthlyCharges** -- The amount charged to the customer monthly

**TotalCharges** -- The total amount charged to the customer

**Churn** -- Whether the customer churned or not (Yes or No)

## How do I get Churny Jane?
Tasks to achieve this project involved:

1.  Hypothesis formation and Data Processing - Importing the relevant libraries and modules,
    Cleaning of Data, Check data types, Encoding Data labels etc.

2.  Data Evaluation -- Perform bivariate and multivariate analysis, Explotory Data Analysis

3.  Build & Select Model -- Train Models on dataset and select the best
    performing model.

4.  Evaluate your chosen Model.

5.  Model Improvement -- Hyperparameter tuning and evaluate improvement

6.  Future Predictions - Test model on fresh data


## What Happens to Jane afterwards?
Final phase of the project involves:
1. Saving the model
2. Assessing model's impact on the business
- Key Insights and Conclusion. - Summarize key discoveries and provide recommendations for future enhancement.
3. Deployment.
- check my blog on Medium for more details into my thought process during my search [mission](https://medium.com/@pamelakushika/whos-leaving-next-097b2c5b3da1) for Churn Jane Doe within Telco.