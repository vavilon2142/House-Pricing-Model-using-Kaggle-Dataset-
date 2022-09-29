# House-Pricing-Model-using-Kaggle-Dataset-
Here's my attempt to predict prices for houses with 75 independant variables.
In short, listed all features. Looked at their descriptive facts. Deleted 5 features due to large amount of missing data.\
Looked at the distributions for numerical features. Didn't adjust the skew (outlayers), i thought the model should be able to consider potential skewness in future \
datasets. Instead, i scaled everything with StandardScaler (x-u)/s. With regards to dependant (Y) variable, i scaled it with logarithm base 10, so it will be easier to convert the variable back to it's understandable scaling (nominal values for prices). For modelling, i used RandomForrestRegressor and LinearRegression. With respect to Linear Regression, i wanted to use PCA for my features ( since there are 75 dimentions and it's complex for plotting) but i will save to my next analysis. 
