# Prediction of Wild Blueberry Yield

Metric used - Mean Absolute Error\
There are total of 18 Features\
Feature to be predicted - yield\
Problem Type - Regression

Features Unit Description\
Clonesize m2 The average blueberry clone size in the field\
Honeybee bees/m2/min Honeybee density in the field\
Bumbles bees/m2/min Bumblebee density in the field\
Andrena bees/m2/min Andrena bee density in the field\
Osmia bees/m2/min Osmia bee density in the field\
MaxOfUpperTRange ℃ The highest record of the upper band daily air temperature during the bloom season\
MinOfUpperTRange ℃ The lowest record of the upper band daily air temperature\
AverageOfUpperTRange ℃ The average of the upper band daily air temperature\
MaxOfLowerTRange ℃ The highest record of the lower band daily air temperature\
MinOfLowerTRange ℃ The lowest record of the lower band daily air temperature\
AverageOfLowerTRange ℃ The average of the lower band daily air temperature\
RainingDays Day The total number of days during the bloom season, each of which has precipitation larger than zero\
AverageRainingDays Day The average of raining days of the entire bloom season



I have used 7 different types of algorithms\
1.Linear Regression\
2.KNN\
3.SVM\
4.Random Forest\
5.Gradient Boosting\
6.XGBoost\
7.LGBRegressor\
Out of these 6 algorithms XGBoost has got least MAE score of 351
