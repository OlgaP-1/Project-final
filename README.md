# Project-final
American Express - Default Prediction Predicting the likelihood that a customer will default on their credit card balance in the future, based on their monthly customer profile. 
Data taken from Kaggle website: https://www.kaggle.com/competitions/amex-default-prediction/data  
The dataset contains aggregated profile characteristics for each client at each discharge date. 
The functions are anonymized and normalized and fall into the following general categories:
D_* = Delinquency variables
S_* = Spend variables
P_* = Payment variables
B_* = Balance variables
R_* = Risk variables
with the following features being categorical:

['B_30', 'B_38', 'D_114', 'D_116', 'D_117', 'D_120', 'D_126', 'D_63', 'D_64', 'D_66', 'D_68']

Task is to predict, for each , the probability of a future payment default ().customer_IDtarget = 1

Files
train_data.csv - training data with multiple statement dates per customer_ID
train_labels.csv - label for each targetcustomer_ID
test_data.csv - corresponding test data; your objective is to predict the label for each targetcustomer_ID
sample_submission.csv - a sample submission file in the correct format
