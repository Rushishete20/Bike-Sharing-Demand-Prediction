# Bike-Sharing-Demand-Prediction

AlmaBetter Verfied Project - https://grow.almabetter.com/
![image](https://github.com/Rushishete20/Bike-Sharing-Demand-Prediction/assets/139244240/d073bd44-8226-4b85-a567-72c097e87a09)

ML Supervised- Developed a regression model using algorithms such as Random Forest and XGBoost to predict the hourly demand of bikes.Performed hyperparameter tuning techniques and achieved R2 score of 92% using XGBoost model and reduced the public waiting time significantly.

![image](https://github.com/Rushishete20/Bike-Sharing-Demand-Prediction/assets/139244240/0773b671-defa-4c88-a5e3-8f8e6f589b14)


# 📖 Random Forest Regression 
Regression is the other task performed by a random forest algorithm. A random forest regression follows the concept of simple regression. Values of dependent (features) and independent variables are passed in the random forest model.

In a random forest regression, each tree produces a specific prediction. The mean prediction of the individual trees is the output of the regression. This is contrary to random forest classification, whose output is determined by the mode of the decision trees’ class.

Although random forest regression and linear regression follow the same concept, they differ in terms of functions. The function of linear regression is y=bx + c, where y is the dependent variable, x is the independent variable, b is the estimation parameter, and c is a constant. The function of a complex random forest regression is like a blackbox.
![image](https://github.com/Rushishete20/Bike-Sharing-Demand-Prediction/assets/139244240/3bc821d7-c473-4bc4-a486-0c7517852991)


# 📖 XGboost 
XGBoost is a powerful approach for building supervised regression models. The validity of this statement can be inferred by knowing about its (XGBoost) objective function and base learners. The objective function contains loss function and a regularization term. It tells about the difference between actual values and predicted values, i.e how far the model results are from the real values. The most common loss functions in XGBoost for regression problems is reg:linear, and that for binary classification is reg:logistics. Ensemble learning involves training and combining individual models (known as base learners) to get a single prediction, and XGBoost is one of the ensemble learning methods. XGBoost expects to have the base learners which are uniformly bad at the remainder so that when all the predictions are combined, bad predictions cancels out and better one sums up to form final good predictions.

![image](https://github.com/Rushishete20/Bike-Sharing-Demand-Prediction/assets/139244240/0d8402a7-46da-4439-b364-a724e91f5d21)
![image](https://github.com/Rushishete20/Bike-Sharing-Demand-Prediction/assets/139244240/51f7d209-260c-4adb-9995-628cec5a7427)
# 📋 Execution Instruction
The order of execution of the program files is as follows:

1) final_notebook_Bike_Sharing_Demand_Prediction.ipynb

This file must be executed, to define all the functions and variables required for regression operations which leads to the production of the model.h5 file. and to evaluate the model performance on unseen data
![image](https://github.com/Rushishete20/Bike-Sharing-Demand-Prediction/assets/139244240/5d2532d3-066c-45ba-aa30-03cfff1c5281)
