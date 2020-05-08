Housing Price Prediction Project

My project aims to predict the sale price of houses. This data comes from this Kaggle competition: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

I began with a baseline that predicts only the mean house price from the training data for each house, but this model does very poorly (of course). A linear regression model on the numeric columns has an R-Squared Score of 0.78. I tried a Ridge regression model to try to manage the multicollinearity between my features but it did not perform any better. In the future I will try to use more features and maybe encode some of the discrete features.