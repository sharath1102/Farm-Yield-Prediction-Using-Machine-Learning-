# Farm-Yield-Prediction-Using-Machine-Learning-
The Farm Yield Prediction Project is designed to predict crop yields using machine learning models.

# Overview
The Farm Yield Prediction Project uses machine learning techniques to predict the yield of crops based on various environmental and agricultural factors. The dataset includes multiple features such as Crop Type, Farm Area, Irrigation Type, Fertilizer Used, Pesticide Used, Yield, Soil Type, Season, and Water Usage. The project employs machine learning models such as Linear Regression, Random Forest, XGBoost, CatBoost, and LGBM Regressor to develop accurate predictions, with CatBoost showing the best performance.

# Features
Dataset: Includes features like crop type, irrigation type, soil type, and various other agricultural inputs.

Models Used:

Linear Regression

Random Forest

XGBoost

CatBoost (Best performing model)

LGBM Regressor

Performance: The CatBoost model provides the best performance for predicting crop yield.

# Usage
1. Predict Crop Yield
   
users can input the following parameters:

Crop Type

Farm Area

Irrigation Type

Fertilizer Used

Pesticide Used

Soil Type

Season

Water Usage

The system will use the trained machine learning model to predict the crop yield based on the entered values.


2. Model Performance

   
The project evaluates multiple models for accuracy, including RMSE, R², and other metrics. The CatBoost model showed the best performance and is used as the final prediction model.

# Dependencies

Python 3.x

Flask: For the web interface

pandas: For data manipulation

numpy: For numerical operations

scikit-learn: For machine learning algorithms

catboost: For the CatBoost model

xgboost: For the XGBoost model

lightgbm: For the LGBM Regressor
