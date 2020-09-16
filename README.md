# IEEE-CIS-Fraud-Detection

![Dataset](https://img.shields.io/badge/Dataset-Kaggle-blue.svg)  ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg)  ![Library](https://img.shields.io/badge/Library-sklearn&Xgboost-orange.svg)  ![DataSource](https://img.shields.io/badge/DataSource-Vesta_crop-cyan.svg)

Predicting the probability that an online transaction is fraudulent.

## data description
Source:Vesta Corp

https://www.kaggle.com/c/ieee-fraud-detection/data

predicting the probability that an online transaction is fraudulent, as denoted by the binary target isFraud.

The data is broken into two files identity and transaction, which are joined by TransactionID. Not all transactions have corresponding identity information.

#### Categorical Features - Transaction
>ProductCD

>card1 - card6

>addr1, addr2

>P_emaildomain

>R_emaildomain

>M1 - M9

#### Categorical Features - Identity
>DeviceType

>DeviceInfo

>id_12 - id_38
