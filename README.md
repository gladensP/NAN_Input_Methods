# NAN_Input_Methods
This is an analysis of different null values input methods and their effect on the performance of a machine learning algorithm.


# Description
I analysed three different input methods on the Linear Regression model and the XGBoost Regressor model. The input methods are :
- Mean Imputation
- Median Imputation
- KNN (K Nearest Neighbors) Imputation

# Results
![results](https://user-images.githubusercontent.com/64794688/205170035-5be82231-812a-4fb9-b74b-baf7ef254f4b.JPG)
- Accuracy Score: For LinearRegression, all Imputation Methods have very low accuracy score(some hyperparameter tuning and more data preprocessing can take care of this) with the Mean Input method having the best accuracy score followed by Median and then KNN. For XGBRegressor, the KNN Input method has the best accuracy score followed by Median and then Mean.

- Mean Squared Error: For LinearRegression, the Median input method has the best MSE followed by Mean and then KNN. For XGBRegressor, the Median input method again has the best MSE followed by KNN and then Mean.

- Mean Absolute Error: For LinearRegression, the Mean input method has the best MAE followed by Median and then KNN. For XGBRegressor, the Median input method has the best MAE followed by KNN and then Mean.
