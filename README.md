Employee Salary Prediction

Introduction
This project aims to predict employee salaries based on multiple factors, including years of experience, education level, job title, and department. The goal is to help HR teams, recruiters, and managers make fair, data-driven compensation decisions. We utilized a dataset with thousands of records containing relevant features to train and evaluate different regression models.

Data Preprocessing

Handling Missing Values: We checked the dataset for missing values and removed or imputed them as necessary to ensure clean input for the models.

Encoding Categorical Variables: Categorical features such as job roles and education levels were encoded using one-hot encoding to make them suitable for machine learning algorithms.

Model Building and Evaluation

Model Selection: We experimented with multiple regression algorithms, including Linear Regression, Decision Tree Regressor, and Random Forest Regressor. Hyperparameter tuning was done using GridSearchCV to find the best model configuration.

Model Evaluation: Model performance was evaluated using standard regression metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²). These metrics helped assess how well the model predicts salaries on unseen data.

Feature Importance
The feature importance analysis revealed which factors contribute most to salary prediction, helping HR teams understand the key drivers behind salary variations.

Results: The Random Forest model achieved the highest R-squared score and lowest errors, proving to be the best model for this dataset.

The Decision Tree model showed good results but was slightly less accurate than the Random Forest. The Linear Regression model performed adequately but struggled to capture non-linear relationships in the data.

Conclusion: The project demonstrates the practical use of machine learning for predicting employee salaries. The Random Forest model emerged as the most reliable choice, highlighting the value of using robust ensemble methods for regression tasks. The feature importance analysis also provided clear insights into which factors most strongly affect salary, making this tool useful for HR analytics and compensation planning.

Usage:

1]Install the required Python libraries from requirements.txt.

2]Open and run the Jupyter notebook or Python script to train the model or make new salary predictions.
