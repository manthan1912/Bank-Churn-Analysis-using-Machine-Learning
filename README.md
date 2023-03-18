# Bank Churn Analysis using Machine-Learning

## Dataset Source
https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset

## Description
The dataset consists of 10000 samples and 12 measurements.
The sample count of group of interest (churn = '0') is 7963 and of group not of interest (i.e. churn = '1') is 2037. 
The features in the dataset are:
1. Customer_id :- Unique ID of a particular customer
2. Credit Score:- It is the credit score of each customer
3. Country:- Country of residence of the customer
4. Gender:- The sex of the customer
5. Age:- The age of the customer
6. Tenure :- Number of years the customer has Bank Account in that Bank
7. Balance :- Amount of money in the account of the customer
8. Products Number :- Number of Products the customer opted from that Bank
9. Credit Card - Customer opted for credit card or not
10. Active Member - Is the customer active or not
11. Estimated Salary - Estimated salary/income of the customer
12. Churn (Target) - a customer still a customer of that bank or not. 0 means 'not churn' or still a customer. '1' means 'churn' or the customer has stopped being the customer.


## Objective
The objective is to train various ML models that returns the probability of a customer to churn. This is a binary classification problem and the performance of the model is measured using 'accuracy' metric. The program runs through 5-fold validation to obtain the error rates of each fold and display the mean error rates of the various models.
The models implemented are:
* KNN with k = 1
* KNN with k = 5
* KNN with k = 10
* ANN with some parameters
* ANN with tuned hyper-parameters


## Installation
Python 3.7+ is required to run code from this repo.
```bash 
$ git clone https://github.com/manthan1912/Bank-Churn-Analysis-using-Machine-Learning.git
$ cd Bank-Churn-Analysis-using-Machine-Learning
```

Now let's install the requirements. 

```bash
$ pip install -r requirements.txt
```
