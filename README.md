Name: Aditya Prasad Sahu
SIC: 23bcsb76
CSE D2 (Lab Roll 13)
Class Roll 26

How i did?
Preprocessing: Handled missing values, one-hot encoded categorical features (like education_level and loan_purpose), and scaled numerical features.
Model: Used AdaBoost with decision stumps (max_depth=1) and 200 estimators.
Performance: Achieved a test AUC
Fairness Check: Computed AUC across subgroups—some education levels or loan purposes may show performance gaps, which is important for fairness auditing.
