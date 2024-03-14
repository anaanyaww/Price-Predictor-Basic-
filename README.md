# Price-Predictor-Basic-
Real Estate - Price Predictor: Python script predicts housing prices via machine learning. Loads data, trains regressors, selects best model, and saves it for future use.
The script begins by importing necessary libraries and loading the dataset from a CSV file. Exploratory data analysis (EDA) is conducted, including inspecting data types, checking for missing values, and exploring correlations between features and the target variable (housing prices).

The script implements train-test splitting using both manual splitting and stratified splitting methods. Various machine learning models such as Linear Regression, Decision Tree Regression, and Random Forest Regression are utilized to predict housing prices. Feature scaling is performed using pipelines to ensure robust model training.

Evaluation of the model's performance is carried out using mean squared error (MSE) and cross-validation techniques. The model is then saved using joblib for future use. Finally, the saved model is loaded to predict housing prices for new data.

The Python script is well-documented with comments explaining each step of the process, making it easy to understand and reproduce the workflow.
