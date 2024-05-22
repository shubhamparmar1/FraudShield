# FraudShield - Fraud Detection in Financial Transactions

## Overview
This project aims to develop a machine learning model for proactive fraud detection in financial transactions. The dataset contains information about various transactions, including transaction type, amount, balance changes, and whether the transaction is fraudulent or not. By analyzing this data and training machine learning models, we aim to identify patterns and predict fraudulent transactions, thus enhancing security measures for financial systems.

## Dataset
The dataset used in this project is provided in CSV format, containing 6,362,620 rows and 10 columns. Each row represents a transaction, and the columns include:
- `step`: Unit of time in the simulation (1 step = 1 hour)
- `type`: Type of transaction (CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER)
- `amount`: Amount of the transaction in local currency
- `nameOrig`: Customer initiating the transaction
- `oldbalanceOrg`: Initial balance before the transaction
- `newbalanceOrig`: New balance after the transaction
- `nameDest`: Recipient of the transaction
- `oldbalanceDest`: Initial balance of the recipient before the transaction
- `newbalanceDest`: New balance of the recipient after the transaction
- `isFraud`: Binary indicator (1 for fraudulent transaction, 0 otherwise)
- `isFlaggedFraud`: Binary indicator for flagged illegal attempts

## Results
The machine learning models trained in this project achieve high precision, recall, and F1-score in detecting fraudulent transactions. The key factors predicting fraudulent transactions include transaction amount, account balances, and transaction types.
