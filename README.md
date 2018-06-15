# CreditCardFraud

## Git
cd Desktop/
cd CreditCardFraud/
echo "# CreditCardFraud" >> README.md
git init
git add .
git commit -m "2 commit"
git remote add origin https://github.com/YuTaNCCU/CreditCardFraud.git
git push -u origin master

## Data
https://www.kaggle.com/mlg-ulb/creditcardfraud/downloads/creditcard.csv/3

## Ref
#### 原始比賽網址：
https://www.kaggle.com/mlg-ulb/creditcardfraud
#### 處理不平衡資料+SVM+KNN+LgoitRegression+一層NN：
https://www.kaggle.com/janiobachmann/credit-fraud-dealing-with-imbalanced-datasets
#### 張量流：
https://www.kaggle.com/currie32/predicting-fraud-with-tensorflow
#### 如何評估不平衡資料：
https://stats.stackexchange.com/questions/338826/auprc-vs-auc-roc

## Context
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

## Content
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

