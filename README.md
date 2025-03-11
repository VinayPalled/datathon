Restaurant Cost Prediction Model
This repository contains a machine learning project focused on predicting the dining cost at various restaurants. The dataset used includes features such as online ordering availability, reservation options, restaurant type, cuisines offered, location, and previous customer reviews. The model leverages preprocessing techniques like encoding categorical variables and normalizing numerical features like votes using logarithmic transformation.

Data Preprocessing
Handling missing values and transforming features to prepare for model training.
Frequency encoding of categorical features to convert them into numerical format.
Dropping less relevant features to streamline the model input.
Feature Engineering
Log transformation of the 'votes' feature to normalize its distribution.
Creation of dummy variables for categorical features to aid in model performance.
Model Development
Utilized multiple regression models including Support Vector Regression (SVR) and Decision Tree Regression.
Evaluation of models based on metrics like MSE, RMSE, MAE, and MAPE to understand their performance.
Output
Final predictions are adjusted and formatted appropriately before saving to a CSV file for submission or further analysis.
