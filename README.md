# House Price Prediction using Machine Learning (Linear Regression)
# Project Overview
This project focuses on predicting house prices using a machine learning model based on linear regression. The dataset used contains various features of houses, such as the average area, price and address which are used to predict the final selling price. This project demonstrates the entire workflow of building a predictive model, from data preprocessing to model evaluation.

# Features
Data Cleaning and Preprocessing  
Exploratory Data Analysis (EDA)  
Feature Engineering  
Model Building and Training  
Model Evaluation and Validation   
Visualization of Results  
# Dataset
The dataset used for this project is sourced from Kaggle and includes the following key features:  
Avg area income    
Avg area house age  
Avg area number of rooms  
Area population  
Address  
Price   
# Installation
To run this project, ensure you have Python installed along with the following necessary libraries:  
Numpy  
Pandas  
Matplotlib  
Scikit learn  
Seaborn  

# Project Structure
data/: Contains the dataset files.  
notebooks/: Jupyter notebooks for data exploration and model building.  
src/: Source code for data processing, model training, and evaluation.  
README.md: Project overview and instructions.  
# Usage
## Data Preprocessing:

Handle missing values.  
Convert categorical features into numerical values using one-hot encoding.  
Feature scaling and normalization.  
## Exploratory Data Analysis (EDA):

Visualize data distributions and relationships between features.  
Identify correlations between features and the target variable.  

## Model Building:

Split the dataset into training and testing sets.  
Train a Linear Regression model using the training set.  
Evaluate the model using the testing set.  
## Model Evaluation:

Use metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared to evaluate the model's performance.  
Visualize the model's predictions versus actual values.

# Results
MSE: 9542801978.105497  
RMSE: 97687.2662024355  
MAE: 79080.67352476912  
R2 Score: 0.9132191795707956  

Achieved a predictive accuracy of 91.3% on test data through model evaluation and fine tuning.   

The results indicate the model's accuracy and potential areas for improvement, such as feature selection and engineering, or trying more advanced regression techniques.

# Conclusion
This project provides a comprehensive approach to predicting house prices using linear regression. By following the steps outlined, you can build and evaluate your own predictive models, gaining insights into the process of machine learning model development and deployment.
