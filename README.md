# Project-2
Online Payment Fraud Detection with Machine Learning

To identify online payment fraud with machine learning, we need to train a machine learning model for classifying fraudulent and non-fraudulent payments. For this, we need a dataset containing information about online payment fraud, so that we can understand what type of transactions lead to fraud. For this task i collected the data which contains historical information about fraudulent transactions which can be used to detect fraud in online payments. Below are all the columns from the dataset I’m using here:

step: represents a unit of time where 1 step equals 1 hour

type: type of online transaction

amount: the amount of the transaction

nameOrig: customer starting the transaction

oldbalanceOrg: balance before the transaction

newbalanceOrig: balance after the transaction

nameDest: recipient of the transaction

oldbalanceDest: initial balance of recipient before the transaction

newbalanceDest: the new balance of recipient after the transaction

isFraud: fraud transaction.

Checked whether the dataset has any null values or not.Explored the transaction types.Plotted pie chart to find the distribution of transaction types.Checked the correlation.Then transformed the categorical features into numerical and transformed the values of the isFraud column into No Fraud and Fraud labels to have a better understanding of the output.

Divided the data into train and test sets,then created DesicionTreeClassifier model by using Sklearn and trained it.Then we can Classify whether a transaction is a fraud or not by feeding about a transaction into the model.

Python Libraries used:Numpy,Pandas,Plotly,Sklearn

Machine Learning model:DecisionTreeClassifier
