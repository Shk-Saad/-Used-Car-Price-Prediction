# Used-Car-Price-Prediction
Developed a machine learning model on the car dataset, predicting used car prices and providing market-driven suggestions for new sellers.

1.Data Collection:
- The script collects data of Used Car.
- The dataset comprises 13 columns and 15,411 rows.

2.Data Cleaning:
- Handles missing values, duplicates, checks data types, and provides a basic understanding of the dataset.

3.Feature Engineering:
- Removes unnecessary columns like 'car_name' and 'brand'.
- Encodes categorical features using one-hot encoding for non-ordinal columns.
- Splits the dataset into training and testing sets.

4.Model Training and Model Selection:
- Utilizes various regression models for predicting car prices, including Linear Regression, Lasso, Ridge, K-Neighbors Regressor, Decision Tree, Random Forest Regressor, and AdaBoost 
  Regressor.
- Evaluates each model's performance on both the training and testing sets, measuring metrics like Root Mean Squared Error, Mean Absolute Error, and R2 Score.

5.Hyperparameter Tuning:
- Uses Randomized Search Cross Validation to find optimal hyperparameters for some of the models (K-Neighbors Regressor, Random Forest Regressor, and AdaBoost Regressor).

6.Retraining with Best Parameters:
- Retrains models with the identified best hyperparameters.
- Evaluates and compares the performance of the tuned models on the training and testing sets.

Build and optimizing machine learning models for predicting used car prices. It includes data cleaning, feature engineering, model training, and hyperparameter tuning to enhance predictive accuracy. The final models' performance metrics are assessed to provide insights into their effectiveness in predicting car prices.
