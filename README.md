# Bulldozer-Price-Prediction

#Data:
It's historical sales data of bulldozers. Including things like, model type, size, sale date and more.
There are 3 datasets:
Train.csv - Historical bulldozer sales examples up to 2011 (close to 400,000 examples with 50+ different attributes, including SalePrice which is the target variable).
Valid.csv - Historical bulldozer sales examples from January 1 2012 to April 30 2012 (close to 12,000 examples with the same attributes as Train.csv).
Test.csv - Historical bulldozer sales examples from May 1 2012 to November 2012 (close to 12,000 examples but missing the SalePrice attribute, as this is what we'll be trying to predict).

#Evaluation
For this problem, as with many regression evaluations, the goal will be to get this value as low as possible.
To see how well our model is doing, we'll calculate the RMSLE and then compare our results to others on the Kaggle leaderboard.
