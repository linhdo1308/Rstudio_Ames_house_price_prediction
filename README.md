# Ames House Price Prediction (Rstudio)

In this project, the goal is to develop a parsimonious linear predictive model for house prices in Ames, Iowa, using a dataset split into training and test sets (with 1,460 and 1,459 observations, respectively). Model performance benchmark for minimum estimated out-of-sample R^2 is .75.

The target variable, SalePrice, is provided in the training set but omitted from the test set, challenging us to build a model that generalizes well to unseen data.

In this notebook, I will choose 5 predictors representing different aspects of a property namely MSSubClass, HouseStyle, Neighborhood, OverallQual and SaleType. Below is data description:

- SalePrice (target variable) - the property’s sale price in dollars.

- MSSubClass: The building class

- Utilities: Type of utilities available

- Neighborhood: Physical locations within Ames city limits

- OverallQual: Overall material and finish quality

- SaleType: Type of sale

Data dictionary can be found here: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

