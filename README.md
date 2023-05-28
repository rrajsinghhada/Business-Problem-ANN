# Business-Problem-ANN

## Goal 
To leverage a deep learning model in order to address a critical business problem, specifically determining, based on customer information, whether a bank customer is likely to churn or remain loyal.

## Dataset
I utilized a dataset comprising user information along with their churn status, indicating whether they churned or not.

## Overview 
* To begin, I performed feature selection, carefully choosing the columns to be used for training the model. During this process, I opted to exclude irrelevant columns such as customer name, surname, and row number.

* Afterwards, I encoded categorical data by replacing the gender and geography columns, and subsequently applied feature scaling.

* I proceeded to design a powerful architecture for an Artificial Neural Network (ANN) and subsequently fed the training and test data into the model to train the ANN.
* I tested the model for a perticular customer with the information provide.

Result
| 1498 | 97 | 
| ---- | -- |
| 187  | 218|
Accurecy = 85.8 %
