# Automated-Credit-Card-Approval

## Description:
The task for the project is to classify and approve credit cards for customers based on their metadata. 
The dataset used for the project (australian.csv containing data from a credit screening database)
which contains information about 690 credit approval decisions, where the first 14 columns contain the variables on which the
decisions is based (where the relation between the column is unknown), and the final column contains the
decision on whether the person was approved for credit (0 = rejected, 1 = approved).

Dataset Link: http://archive.ics.uci.edu/ml/datasets/statlog+(australian+credit+approval)

## Solution:
From the project's perspective, a good solution to this problem would accurately predict
whether an unseen person (i.e. one not in the dataset will be approved for credit). It is more
costly for the project if it approves someone for credit when they should have been rejected
than it is to reject someone for credit who should have been approved, so the project needs 
to be accurate when predicting approval decisions. 
