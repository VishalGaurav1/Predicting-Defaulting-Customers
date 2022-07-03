# Predicting-Defaulting-Customers
This repository deals with predicting whether a Customer will default on his loan.
Insights:
1)As we move from Grade A to Grade G,the percent of people who are repaying their loans is decreasing and the percent of people who are defaulting is increasing.
2)Among the people who have repaid their loans,around 50% of people have taken loans for mortgage,folowed by rent and others.For the people who defaluted,around 50% of people have taken loans for rent,followed by mortgage and others.
3)Debt consolidation is the major purpose for which a customer takes a loan irrespective of whether he repays it or default.
4)The median loan amount for customers who have repaid their loans is 12000 while The median loan amount for customers who have defaulted their loans is 14000.Also the median annual income for customers who have repaid their loans is 65000 and the median annual income for customers who have defaulted their loans is 59000.
5)Since it is an imbalanced dataset-80% negatives and 20% positives,I have taken f1 score a the performance metric.Among the different models-Logistic Regression,Decision tree classifier,Random Forest classifier and Gbdt,Random Forest classifier is giving the highest f1 score of 0.41.
6)The most important features which will determine whether a customer will default or not are sub-grade,dti and annual income while the least 3 important features are home_ownership_others,purpose_others and pub rec bankrupcies.
