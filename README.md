# L1-and-L2-Regression

**Melbourne Housing Price Prediction**
This project demonstrates predicting housing prices in Melbourne using different linear regression models, including regularized models such as Lasso (L1) and Ridge (L2) regression.

**Dataset**
The dataset Melbourne_housing_FULL.csv contains various features related to houses in Melbourne, such as:
Suburb
Rooms
Type
Method
SellerG
Regionname
Propertycount
Distance
CouncilArea
Bedroom2
Bathroom
Car
Landsize
BuildingArea
Price

**Steps**
**Data Loading and Exploration:**
Loaded the dataset into a DataFrame.
Displayed unique values and the shape of the dataset.

**Data Preprocessing:**
Selected relevant columns for analysis.
Handled missing values by filling with zero or mean where appropriate.
Removed remaining rows with missing values.
Converted categorical variables to dummy variables using one-hot encoding.

**Feature Selection and Splitting Data:**
Prepared the feature matrix X and the target vector y.
Split the data into training and testing sets.

**Model Training and Evaluation:**

**Linear Regression:**
Trained a simple linear regression model.
Evaluated the model on training and testing sets.

**Lasso Regression:**
Trained a Lasso regression model with L1 regularization.
Evaluated the model on training and testing sets.

**Ridge Regression:**
Trained a Ridge regression model with L2 regularization.
Evaluated the model on training and testing sets.

**Results**
The models were evaluated using the R-squared score on both training and testing sets.

**Dependencies**
numpy
pandas
matplotlib
seaborn
scikit-learn
