# Predicting-House-Prices-in-King-County
This project's goal is to forecast house prices in King County, which encompasses Seattle, utilizing a dataset encompassing various attributes of houses sold between May 2014 and May 2015. The dataset offers a valuable resource for assessing straightforward regression models.


## Dataset Overview
The dataset includes the following attributes:

id: Unique identifier for each house
date: Sale date
price: Sale price
bedrooms, bathrooms, sqft_living, sqft_lot, floors, waterfront, view, condition, grade, sqft_above, sqft_basement, yr_built, yr_renovated, zipcode, lat, long, sqft_living15, sqft_lot15

##  Exploratory Analysis
The notebook features exploratory data analysis (EDA) covering:

Price distribution
Relationship between price and living area square footage
Price distribution by house condition
Influence of bathrooms on house price
Correlation analysis
Feature engineering
Model construction and evaluation
Model Development
The notebook includes model development employing various regression algorithms:

Ridge Regression
Lasso Regression
Elastic Net
Random Forest Regression
XGBoost Regression
Support Vector Regression (SVR)
Decision Tree Regression
Evaluation Metrics
Model performance is assessed using:

Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R-squared (R2) score
Conclusion
Based on these evaluation metrics, we identify the most effective model for predicting house prices in King County. Additionally, we offer insights and suggestions for further analysis or enhancement.
