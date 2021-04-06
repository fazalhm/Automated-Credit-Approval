# Automated-Credit-Card-Approval

## Description:
The task for the project is to classify and approve credit cards for customers based on their metadata. 
The dataset used for the project (australian.csv containing data from a credit screening database)
which contains information about 690 credit approval decisions, where the first 14 columns contain the variables on which the
decisions is based (where the relation between the column is unknown), and the final column contains the
decision on whether the person was approved for credit (0 = rejected, 1 = approved).

Dataset Link: http://archive.ics.uci.edu/ml/datasets/statlog+(australian+credit+approval)

## Solution:
From the project's perspective, a good solution to this problem would be to accurately predict
whether an unseen person (i.e. one not in the dataset will be approved for credit). It is more
costly for the project if it approves someone for credit when they should have been rejected
than it is to reject someone for credit who should have been approved, so the project needs 
to be accurate when predicting approval decisions. 
Therefore, the project uses different machine learning classifiers to execute the problem, and 
uses parameter tuning for each classifier to get the best classifier and the parameters for the problem. 
Once, the parameter tuning is completed the classifier is analysed using cross validation method to get an overall
result with the confusion matrix for the project. Since, the best classifier is extracted from the project, it can be then used
for an automated credit card approval system.
The best classifier to use is Random Forest which yields 86% accuracy with the ratio of approving someone for credit 
when they should have been rejected to be low as 12%. 
