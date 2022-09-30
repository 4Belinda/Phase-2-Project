# Predicting  House Prices with Multiple Regression Analysis

**Regression analysis problem**
The analysis aims towards determining a combination of features that is best for constructing a model to predict house prices. The results will help home owners interested in selling their homes by informing them on the important factors to consider in order to improve sale prices.

**Dataset**
The King County Housing dataset that was used contains information about various features for houses. 

**Linear regression**
Simple and multiple linear regression models were built in OLS Statsmodels with price as the dependent variable.

**Results**
Square footage of living space, number of bedrooms and square footage of interior housing living space for the nearest 15 neighbors are the most effective for predicting house prices using a multiple linear regression model. They have a high correlation with price, low multicollinearity and account for a good percentage of price variability. Multiple regression assumptions are satisfied when the features are included in the model.

**Recommendations**
In order for homeowners to sell their homes at a higher price they should expand the square footage of living space. The square footage of neighbors' living space is a positive predictor of price, but homeowners have less control over this factor. However, they can increase sale price by encouraging neighbors to expand the square footage of their living space. Moreover, they should consider reducing the number of bedrooms since the analysis suggests that additional bedrooms reduce the sale price.

**Limitations**
The model has some limitations:
The variables were log-transformed to satisfy regression assumptions. Therefore, any data to be used with the model would have to be subjected to the same preprocessing. Regional differences in housing prices limit applicability of the model to data from other counties. Moreover, removal of outliers from the model suggests that it may be less appropriate in predicting large values.
