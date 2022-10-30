# NYC-Taxin-Trip-Predection
NYC-Taxi-Trip-Time-Prediction
Capstone Project on NYC Taxi Trip Time Prediction Task is to build a model that predicts the total ride duration of taxi trips in New York City. Primary dataset is one released by the NYC Taxi and Limousine Commission, which includes pickup time, geo-coordinates, number of passengers, and several other variables.

Project Files Description This repository includes 1 colab notebook (.ipynb) file and 1 pdf file of project presentation.

About Files: NYC Taxi Trip Time Prediction Capstone Project.ipynb - This file includes Features description, exploratory data Analysis, feature engineering, feature scaling and implemented algorithms for eg. Linear Regression,lasso and Ridge Regression

📋 Summary The given dataset conatins more than 14 lac records and 11 columns. The main goal of this project to predict the trip duration. To get more insights about the dataset, performed Exploratory data analysis to understand the main characteristics of various features. Using existing features, created new features for model building and to interpret data more easily. After analyzing the dataset, it’s found that there is a some inconsistency in some recorded data. The passenger count was high like 7 to 9 passengers in taxi. The travelled distance is very less but trip duration is quite high. There were many outliers in many columns and after analyzing the data, those outliers removed and dataset prepared for model building. Various algorithms apllied on prepared dataset afetr train and test split of dataset. Linear Regression algorithm performed very good on given dataset. It predicted 0.91 R2 score on train and test dataset. Linear Regression predicted good accuracy on train and test dataset.
