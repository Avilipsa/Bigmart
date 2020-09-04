# Bigmart Sales Prediction 

Introduction:

The data scientists at BigMart have collected 2013 sales data for 1559 products 
across 10 stores in different cities. Also, certain attributes of each product 
and store have been defined.

Objective - To build a prediction model which can help in increasing sales of BIGMART stores

Steps we followed in order to build the prediction model - 
1.We began by eliminating the null values.

2.We then checked the correlation between all the features.

3.Then we explored more about the Outlet type,location of the outlet ,their sizes and sales.
Also about the item types and fat contents in them through variety of EDA plots

4.We then converted categorical variables into numerical ones using One Hot Encoding in Data Pre-Processing Step.
As, In One hot encoding, each category of a categorical variable is converted into a new binary column (which is 0 or 1).

5.Before deciding on regression models, we checked the statistical inferences ,we are comparing the independent and dependent variables and check the R square value in order to see the accuracy, followed by heat map correlation.

6. In the final steps we applied various models such as Linear Regression,Random Forest and XGBoostRegressor.
And found that XGboost Regressor gives the highest accuracy of 73.39%.

Why we have choosen the above listed models ?



