# Data Dictionary

## Dataset: Customer Churn Prediction Dataset

This document describes all features used in the Customer Churn Prediction project.

| Feature Name | Description |
|-------------|-------------|
| customerID | Unique identifier assigned to each customer |
| gender | Customer gender |
| SeniorCitizen | Indicates whether the customer is a senior citizen |
| Partner | Indicates whether the customer has a partner |
| Dependents | Indicates whether the customer has dependents |
| tenure | Number of months the customer has remained with the company |
| PhoneService | Indicates whether the customer subscribes to phone service |
| MultipleLines | Indicates whether the customer has multiple phone lines |
| InternetService | Type of internet service subscribed by the customer |
| OnlineSecurity | Indicates whether online security service is subscribed |
| OnlineBackup | Indicates whether online backup service is subscribed |
| DeviceProtection | Indicates whether device protection service is subscribed |
| TechSupport | Indicates whether technical support service is subscribed |
| StreamingTV | Indicates whether streaming TV service is subscribed |
| StreamingMovies | Indicates whether streaming movie service is subscribed |
| Contract | Customer contract duration |
| PaperlessBilling | Indicates whether paperless billing is enabled |
| PaymentMethod | Method used by the customer for bill payments |
| MonthlyCharges | Monthly amount charged to the customer |
| TotalCharges | Total amount charged to the customer during their subscription period |
| Churn | Indicates whether the customer left the company |

## Target Variable

**Churn**

* **Yes** → Customer has discontinued the service.
* **No** → Customer is still an active customer.

This is the target variable used for training the churn prediction model.

## Feature Categories

### Customer Demographics

* gender
* SeniorCitizen
* Partner
* Dependents

### Customer Account Information

* tenure
* Contract
* PaperlessBilling
* PaymentMethod

### Service Subscription Information

* PhoneService
* MultipleLines
* InternetService
* OnlineSecurity
* OnlineBackup
* DeviceProtection
* TechSupport
* StreamingTV
* StreamingMovies

### Billing Information

* MonthlyCharges
* TotalCharges

### Target Variable

* Churn