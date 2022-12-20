#Health Care

In this project I applied a few number of machine learning algorithms to find the risk level of maternals.
## Data Set
The data set set used in this project is provided by _CSAFRIT_ in Kaggle.
Data has been collected from different hospitals, community clinics, maternal health cares through the IoT based risk monitoring system.

- Age: Age in years when a woman is pregnant.
- SystolicBP: Upper value of Blood Pressure in mmHg, another significant attribute during pregnancy.
- DiastolicBP: Lower value of Blood Pressure in mmHg, another significant attribute during pregnancy.
- BS: Blood glucose levels is in terms of a molar concentration, mmol/L.
- HeartRate: A normal resting heart rate in beats per minute.
- Risk Level: Predicted Risk Intensity Level during pregnancy considering the previous attribute

## Models
The models used in this project are:
- GaussianNB as the baseline model and the accuracy is 0.57
- LogisticRegression with GridSearchCV to find optimal hyperparameters and the accuracy is 0.62
- DecisionTreeClassifier with GridSearchCV to find optimal hyperparameters and the accuracy is 0.77
- SVC  with GridSearchCV to find optimal hyperparameters and the accuracy is 0.75
- KNeighborsClassifier with GridSearchCV to find optimal hyperparameters and the accuracy is 0.70
- KNeighborsClassifier with GridSearchCV to find optimal hyperparameters and the accuracy is 0.70
- AdaBoostClassifier and the accuracy is 0.78
- GradientBoostingRegressor and the accuracy is 0.76
- xgboost with GridSearchCV to find optimal hyperparameters and the accuracy is 0.78
