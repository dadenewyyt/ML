# ML
Machine Learning 

#California Housing Price Prediction
#Overview
This repository contains a Python script for predicting housing prices in California using the California Housing dataset. The script utilizes the XGBoost regression model for training and evaluation.

#Dependencies
Ensure you have the following Python libraries installed:

NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
XGBoost
You can install them using the following command:

bash
Copy code
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
Dataset
The California Housing dataset is loaded using scikit-learn's fetch_california_housing function. The dataset contains information about median income, house age, average rooms, average bedrooms, population, average occupancy, latitude, and longitude, with the target variable being the median house value.

Data Preprocessing
The dataset is loaded into a Pandas DataFrame, and basic exploratory data analysis is performed. Duplicate records are removed, and missing values are checked (no missing values found).

Exploratory Data Analysis (EDA)
Descriptive statistics and correlation analysis are conducted to understand the relationships between features. A heatmap is used to visualize the correlation matrix.

Model Training
The dataset is split into training and test sets. The XGBoost regression model is trained on the training set.

Model Evaluation
The model is evaluated using R-squared and Mean Squared Error (MSE) on both the training and test sets.

Results
The XGBoost model shows promising performance with an R-squared of approximately 0.9446 on the training set and 0.9854 on the test set. The MSE on the test set is around 0.0191.

Visualization
A scatter plot is created to visualize the actual prices against the predicted prices on the training set.

Feel free to explore and modify the script for further experimentation and improvement.
