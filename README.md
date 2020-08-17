# Forecasting sales of Walmart retail goods

This project explores different ways to forecast unit sales of products with the objective of zeroing in on the model with the least error. A special focus is given on ensemble models during the study.

The dataset used for the study is https://www.kaggle.com/c/m5-forecasting-accuracy/data

## Dataset

Data is made available for 3049 items sold in 10 Walmart stores located across 3 States of the USA: California, Texas, and Wisconsin. This data includes item level, department, product categories, and store details. In addition, it has explanatory variables such as price, promotions, day of the week, and special events. The aim is to forecast the daily sales of these products for the next 28 days. This translates to the prediction of 42,840 hierarchical series based on historical data spanning more than 1900 days.

## Analysis

Ensembles are known to be among the most competitive forms of solving predictive tasks. Diversity among the individual components of ensembles is known to be a key element to generate a successful model. Gradient Boosting is a well-known type of ensembles. The main purpose of this project is the presentation and experimental analysis of the improvement of prediction accuracy of two popular ensembles XGBoost and Light GBM on forecasting time series data. 

## Conclusion

It can be seen that although the ensemble models have comparable accuracies, they significantly outperform the SARIMAX model. 
