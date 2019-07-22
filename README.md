# Customer-Credit-Card-transaction-predicition
Predict averaged expected transaction of customer based on the previous 3 months user data
1) Install the required packages 
2) Run the attached jupyter notebook in sequence. 
3) Attached data dictionary to understand the data. 
4) Model uses ensembling on the predicitons of regressions models from sklearn, LGB, XGB. 
5) Ensembling is done by stacking predicitons and applying LGB on the stacked predictions. The idea here is that by applying regression on stacked predcitons we are trying to get weightage to each model from the regression
6) We then use these weights in ensembling to get the predcition for next 3 months avg usage. 
7) TODO : try ARIMA, auto-encoder models. 
