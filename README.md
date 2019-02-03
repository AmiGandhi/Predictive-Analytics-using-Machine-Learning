# Regression-and-Classification-Techniques

The main aim is to perform classification and regression using various techniques along with hyper-parameter tuning in order to predict the price for the housing dataset. And finally come up with the best model which better predicts the target variable, price here.

# DATASET:

The original dataset for King County House Price prediction can be found on https://www.kaggle.com/harlfoxem/housesalesprediction/home This dataset contains house sale prices for King County, which includes Seattle. It includes houses sold between May 2014 and May 2015. Here, a cleaned dataset is being used where the categorical features are already one-hot encoded.

Below is the description of the dataset used :

price:- It is the price of house which we have to predict so this is our target variable and aprat from it are our features.
bedrooms :- It determines number of bedrooms in a house.
bathrooms :- It determines number of bathrooms in a bedroom of a house.
sqft_living :- It is the measurement variable which determines the measurement of house in square foot.
sqft_lot : It is also the measurement variable which determines square foot of the lot.
floors: It determines total floors means levels of house.
waterfront : This feature determines whether a house has a view to waterfront; 0 means no, 1 means yes.
view : This feature determines whether a house has been viewed or not; 0 means no, 1 means yes.
condition : It determines the overall condition of a house on a scale of 1 to 5.
grade : It determines the overall grade given to the housing unit, based on King County grading system on a scale of 1 to 11
sqft_above : It determines square footage of house apart from basement.
sqft_basement : It determines square footage of the basement of the house.
yr_built : It detrmines the date of building of the house.
yr_renovated : It detrmines year of renovation of house.
zipcode : It determines the zipcode of the location of the house.
lat : It determines the latitude of the location of the house.
long : It determines the longitude of the location of the house.
sqft_living15 : Living room area in 2015(implies-- some renovations)
sqft_lot15 : lotSize area in 2015(implies-- some renovations)

# METHODS USED:

### For Part A:
Bagging Algo : Random Forest Classifier
Boosting Algo : XGBoost Classifier
### For Part B:
Logistic Regression
### For Part C:
Bagging Algo : Random Forest Regressor
Boosting Algo : XGBoost Regressor
### For Part D:
Linear Regression with Regression Regularization (Ridge Regression and Lasso Regression)
### For Part E:
Decision Tree Regressor

# RESULTS:

Both classification and regression models are evaluated to find the AUC and accuracy (MAPE) respectively for how well housing price was predicted. Tuned XGBoost model gave highest AUC of about 0.9153 and accuracy (MAPE) of about 87.35% for regression analysis. The results section consisting of combined result table for both classification and regression is present towards the end of jupyter notebook

# CONCLUSION:

Hence, the conclusion is that a tuned XGBoost model outperforms other models for both classification and regression problem in house price prediction.
