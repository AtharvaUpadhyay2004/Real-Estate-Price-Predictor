# Real-Estate-Price-Predictor
ML data prediction model which gives estimate of the MEDV on the basis of features.

The code is a machine learning pipeline for real estate price prediction. It begins by importing necessary libraries and loading real estate data from a CSV file. Exploratory data analysis is performed by displaying the data's head, providing information about its structure, and generating descriptive statistics.
Visualizations such as histograms and scatter plots are created to gain insights into the data. The dataset is then split into training and testing sets using stratified random sampling to ensure unbiased representation. The data is prepared by handling missing values and scaling numerical features using a pipeline.
Different models, including Linear Regression, Decision Tree Regressor, and Random Forest Regressor, are selected and trained on the prepared training data. Model evaluation is conducted using mean squared error (MSE) and root mean squared error (RMSE).
Cross-validation is performed to assess model performance, and the trained Random Forest Regressor model is saved. The model is tested on the test data, and the final RMSE is calculated.
