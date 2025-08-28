# Customer Churn Analysis Dataset

This dataset contains information about customers of a telecom service provider, "Databel," and is designed for analyzing customer churn. The data includes demographic details, contract information, service usage, and charges.

## Table Overview

The dataset consists of the following key categories:

### 1. Customer Status
This section identifies the customer and their churn status.

| Field Name | Description |
| :--- | :--- |
| `Customer ID` | A unique identifier for each customer. |
| `Churn Label` | Indicates if the customer churned. Values: `Yes`, `No`. |
| `Churn Reason` | The specific reason provided for the customer ending their contract. |
| `Churn Category` | A high-level group categorizing multiple churn reasons for easier analysis. |

### 2. Demographics
This section contains basic demographic information about the customers.

| Field Name | Description |
| :--- | :--- |
| `Gender` | The gender of the customer. Values: `Male`, `Female`, `Prefer not to say`. |
| `Under 30` | Indicates if the customer is under 30 years old. Values: `Yes`, `No`. |
| `Senior` | Indicates if the customer is 65 years or older. Values: `Yes`, `No`. |
| `Age` | The exact age of the customer. |

### 3. Contract Information
This section details the terms and location of the customer's contract.

| Field Name | Description |
| :--- | :--- |
| `Contract Type` | The type of contract the customer is on. Values: `Month-to-Month`, `One Year`, `Two Year`. |
| `Payment Method` | The customer's preferred payment method. Values: `Credit Card`, `Direct Debit`, `Paper Check`. |
| `State` | The code of the U.S. state where the customer resides. |
| `Phone Number` | The phone number of the customer. |
| `Group` | Indicates if the customer is part of a cheaper group contract. Values: `Yes`, `No`. |
| `Number of customers in a group` | The total number of customers part of the same group contract. |

### 4. Subscription Types & Charges
This section covers service usage, plan details, and financial charges.

| Field Name | Description |
| :--- | :--- |
| `Account Length (in months)` | The number of months the customer has been with Databel. |
| `Local Calls` | The quantity of local (within the U.S.) calls made by the customer. |
| `Intl Calls` | The quantity of international calls made by the customer. |
| `Intl Mins` | The total number of minutes spent on international calls. |
| `Intl Active` | Indicates if the customer made any international calls. Values: `Yes`, `No`. |
| `Intl Plan` | Indicates if the customer has a premium plan for free international calls. This affects the monthly charge. Values: `Yes`, `No`. |
| `Extra International Charges` | Extra charges incurred for international calls by customers without an international plan. |
| `Customer Service Calls` | The number of calls the customer made to customer service. |
| `Avg Monthly GB Download` | The average monthly download volume, in gigabytes. |
| `Unlimited Data Plan` | Indicates if the customer has a plan with unlimited download capacity. This affects the monthly charge. Values: `Yes`, `No`. |
| `Extra Data Charges` | Extra charges incurred for data downloads by customers without an unlimited data plan. |
| `Monthly Charges` | The average amount charged to the customer per month. |
| `Total Charges` | The total sum of all monthly charges billed to the customer. |

## Project Goal
The primary goal of this dataset is to perform analysis and build models to predict customer churn. Understanding the factors that lead to churn can help develop strategies for customer retention.
