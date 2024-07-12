# Flight Price Prediction - Machine Learning Project using Flask

## Project Overview
This project is a machine learning-based application designed to predict flight prices. It includes data pre-processing, model training, and a web application to input flight details and get a price prediction.

## Project Flow
1. **GitHub Setup**: Initialize the repository and commit the initial code.
2. **Model Training**:
   - Gather and split data
   - Data pre-processing
   - Model selection (using Learning Curves)
   - Model training
   - Model persistence
3. **Create Input Form**: Develop a form for inputting flight details.
4. **Create the Application**: Build a Flask web application.
5. **Create HTML Templates**: Design templates for the web pages.
6. **Testing on Local Server**: Test the application locally.

## Libraries Used
python
pandas
numpy
sklearn
feature_engine
xgboost
joblib
matplotlib

## Usage
Run the Flask application:
python app.py

## Model Training
### Gather and Split Data: Use the train.csv and val.csv files for training and validation.
###  Data Pre-processing: Handle missing values using SimpleImputer.
###  Scale numerical features with StandardScaler.
### Encode categorical features using OneHotEncoder.
###  Model Selection: Use learning curves to select the best model.
###  Model Training: Train models like Linear Regression, SVR, Random Forest, and XGBoost.
###  Model Persistence: Save the trained model using joblib.
