# Credit-Card-Fraud-Detection-through-Data-Mining
One of the biggest issues facing the credit card industry has been identified as Credit Card Fraud. The two primary concepts are classifying the various forms of credit card fraud and evaluating all of the techniques that have been applied in order to find fraudulent activity.Various strategies can be employed to prevent credit card fraud, dependent on the variety of illegal activities that credit card firms and financial institutions, including banks, encounter. The aim of implementing these strategies and initiatives is to decrease credit card fraud.This Credit Card Fraud Detection project is developed using various data mining techniques. The goal is to develop robust models that can effectively detect fraudulent transactions, thus helping financial institutions and businesses prevent fraudulent activities.

The description for each feature available in this dataset is:
•	Time: the time of transactions.
•	V1 – V28: various attributes of credit card transactions.
•	Amount: amount involved in credit card transactions.
•	Class: whether the given credit card transaction is fraudulent (1) or not (0).


Number of Columns: 31 
Number of Rows: 11959 

This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) Account for 0.172% of all transactions.It contains only numerical input variables which are the result of a PCA transformation. Due to confidentiality issues, this dataset cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal Components obtained with PCA.The only features which have not been transformed with PCA are ‘Time’ and ‘Amount’. Feature ‘Time’ contains the seconds elapsed between each transaction and the first Transaction in the dataset. The feature ‘Amount’ is the transaction Amount, this feature can be used for example-dependent cost-sensitive learning. Feature ‘Class’ is the response Variable and it takes value 1 in case of fraud and 0 otherwise.



