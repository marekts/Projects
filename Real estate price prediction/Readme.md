Real estate price prediction is popular type of task in data science and there are full of datasets for this issue.
I will solve it participating in [Kaggle 'House prices' competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). Kaggle use RMSLE metric for this competition. <br> 

Dataset contains two part: train part with labels (house price) and test part with no price. <br>

I will use supervised machine learning in order to built model which will be predict house prices based on house parameters. <br>
Tools I used: **pandas, numpy, sklearn, xgboost, matplotlib** <br>



I separated the task on a few steps:
  - understanding data
  - deal with empty values
  - feature engineering
  - try a few models (I chose XGBoost ans SVM)
  - model optimization (feature importances and hyperparameter optimization)
  - testing model on test data and upload to Kaggle

I placed data description in separated file 'data_description.txt' due to large amount of text.

Currently score on Kaggle **0.12089 (RMSLE)**.<br>

