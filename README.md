# Salary Prediction

## Objective
Given a job's feature, including years of experience, job type and education level, we're creating a model to predict the salary that should be paid to new employees. 

## Exploratory Data Analysis
![Salary](https://github.com/sharmas412/SalaryPrediction_HR/blob/master/images/SalaryDistribution.png)
![Degree](https://github.com/sharmas412/SalaryPrediction_HR/blob/master/images/Degree.png)
![Major](https://github.com/sharmas412/SalaryPrediction_HR/blob/master/images/Major.png)
![Industry](https://github.com/sharmas412/SalaryPrediction_HR/blob/master/images/Industry.png)
![Experience](https://github.com/sharmas412/SalaryPrediction_HR/blob/master/images/Experience.png)
![Distance](https://github.com/sharmas412/SalaryPrediction_HR/blob/master/images/Distance.png)
![JobType](https://github.com/sharmas412/SalaryPrediction_HR/blob/master/images/JobType.png)
![Company](https://github.com/sharmas412/SalaryPrediction_HR/blob/master/images/CompanyDistribution.png)


## Code
01_EDA : exploratory data analysis of the features and target variable
02_ Processing and Modeling : Preprocess data based on the EDA and train random forest and gradient boosting models and tune hyperparameters to lower the mean squared error. 

# Summary
The model could help HR figure out salary for new employees. The trained model with hyperparameter tuning showed that the gradient boosting model lower the MSE to 356 compared to 1499 of the dummy base model.
