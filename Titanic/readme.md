This is famous **Titanic** dataset. Task is create a model that predicts which passengers survived after disaster. <br>
I solve this issue by participating in [Kaggle competition](https://www.kaggle.com/c/titanic/overview).

The data splited on train and test part. Train part contains colums _'Survived'_ and test part not. 

I handle the task in few steps:
  - quick look on data
  - cleaning dataset 
  - trying few supervised machine learning models with cross validation
  - trying to build some new features
  - hyperparameter optimization 
  - use ensemble voting method to fit final model 
  - final prediction on test part and check it on Kaggle

Final accuracy score on Kaggle: **0.80382** 

<br>

Data description:
  - PassengerId - PassengerId
  - survival -	Survival	(0 = No, 1 = Yes)
  - pclass - 	Ticket class	(1 = 1st, 2 = 2nd, 3 = 3rd)
  - sex -	Sex	
  - Age -	Age in years	
  - sibsp -	number of siblings / spouses aboard the Titanic	
  - parch - of parents / children aboard the Titanic	
  - ticket -	Ticket number	
  - fare -	Passenger fare	
  - cabin -	Cabin number	
  - embarked - 	Port of Embarkation

