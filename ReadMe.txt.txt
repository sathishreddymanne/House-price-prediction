# House Price Prediction

## Overview

This project predicts house prices using Machine Learning techniques. The dataset contains information about residential properties such as total square footage, number of bedrooms, bathrooms, balconies, and location details.

The goal of this project is to analyze housing data, perform data preprocessing, train multiple machine learning models, and compare their performance for house price prediction.

## Dataset

The dataset includes the following features:

* Area Type
* Availability
* Location
* Size (BHK)
* Total Square Feet
* Number of Bathrooms
* Number of Balconies
* Price

## Data Preprocessing

The following preprocessing steps were performed:

* Handled missing values in the dataset.
* Removed the `society` column due to a large number of missing values.
* Filled missing values in numerical columns using appropriate statistical methods.
* Extracted BHK values from the `size` column.
* Converted the `total_sqft` column into numerical format.
* Removed invalid and inconsistent records.
* Performed outlier detection and analysis using boxplots and the IQR method.
* Encoded categorical features such as location and area type.

## Feature Selection

The following features were used for model training:

* BHK
* Total Square Feet
* Bathrooms
* Balconies
* Encoded Location Information
* Encoded Area Type Information

Target Variable:

* Price

## Machine Learning Models Used

The following regression models were trained and evaluated:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. K-Nearest Neighbors Regressor
5. Support Vector Regressor (SVR)

## Feature Scaling

StandardScaler was used to normalize numerical features before training models that are sensitive to feature scales.

## Model Evaluation

Models were evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)

The performance of multiple algorithms was compared, and the best-performing model was selected based on evaluation metrics.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Missing Value Handling
4. Feature Engineering
5. Outlier Analysis
6. Feature Scaling
7. Model Training
8. Model Evaluation
9. Performance Comparison

## Author

Sathish Reddy Manne
