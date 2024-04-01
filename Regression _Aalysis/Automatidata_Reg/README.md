# Regression Model
This model can be used to predict the fare amount of taxi cab rides with reasonable confidence. 
Model metrics:
Net model tuning resulted in:

R^2 0.87, meaning that 86.8% of the variance is described by the model.

MAE 2.1

MSE: 14.36

RMSE 3.8

# Key Insights

The feature with the greatest effect on fare amount was ride duration, which was not unexpected. The model revealed a mean increase of $7 for each additional minute, however, this is not a reliable benchmark due to high correlation between some features. 

The New York City Taxi and Limousine commission can use these findings to create an app that allows users (TLC riders) to see the estimated fare before their ride begins.

The model provides a generally strong and reliable fare prediction that can be used in downstream modeling efforts.
