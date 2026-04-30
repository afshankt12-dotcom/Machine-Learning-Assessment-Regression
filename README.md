# Machine-Learning-Assessment-Regression
House Price Prediction using Regression Algorithms  This project focuses on predicting house prices using machine learning regression techniques. The dataset includes features such as number of bedrooms, bathrooms, square footage, and other property details.
README: House Price Prediction using Regression
This project analyzes housing data from King County, USA, to predict sale prices using various machine learning regression techniques. The implementation is contained within the notebook House Price Prediction using Regression.ipynb.  

## Project Overview
The goal of this project is to build and evaluate models that can accurately estimate house prices based on physical attributes and location data.  

### Dataset
The analysis uses the kc_house_data.csv.csv dataset, which includes 21 features such as:  

Target Variable: price.  

Key Features: sqft_living, bedrooms, bathrooms, floors, waterfront, view, grade, yr_built, and geographic coordinates (lat, long).  

## Workflow
### 1. Data Cleaning & Preprocessing
Missing Values: Handled by dropping any rows containing null entries to ensure data integrity.  

Feature Selection: Dropped non-predictive columns like id and date.  

Feature Scaling: Utilized StandardScaler to normalize the feature set, ensuring that variables with different scales (e.g., square footage vs. number of bedrooms) contribute equally to model performance.  

### 2. Exploratory Data Analysis (EDA)
The notebook includes visualizations to understand the underlying data distribution:  

Histograms: Used to view the distribution of house prices.  

Scatter Plots: Used to identify the relationship between living area (sqft_living) and the target price.  

Boxplots: Used for outlier detection within the price feature.  

### 3. Model Implementation
Three distinct regression algorithms were trained and tested:  

Linear Regression: The baseline statistical model.  

Decision Tree Regressor: A non-linear model capturing more complex data patterns.  

Random Forest Regressor: An ensemble method used to improve prediction accuracy and robustness.  

## Performance Evaluation
Models are compared using standard regression metrics:  

MAE (Mean Absolute Error): Average magnitude of the errors.  

MSE (Mean Squared Error): Measures the average squared difference between estimated and actual values.  

R2 Score: Indicates how well the independent variables explain the variability of the dependent variable.  

## Requirements
To run House Price Prediction using Regression.ipynb, you will need the following Python libraries:  

pandas

numpy

matplotlib

seaborn

scikit-learn
