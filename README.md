# CodeClauseInternship_Predicting-House-Prices
Building a simple linear regression model to predict house prices based on features like the number of bedrooms and square footage.

**Project Title:** Predicting House Prices

**Aim:**  
The aim of this project is to develop a simple linear regression model to predict house prices based on features such as the number of bedrooms and square footage.

**Description:**  
The project involves the following steps:
1. **Data Loading:** The dataset containing information about house prices is loaded from the 'house_prices_dataset.csv' file.
2. **Data Preprocessing:** The dataset is preprocessed by selecting relevant features ('bedrooms' and 'sqft') as input variables (X) and the 'price' as the target variable (y).
3. **Data Splitting:** The dataset is split into training and testing sets using the `train_test_split` function from the `sklearn.model_selection` module.
4. **Model Development:** A linear regression model is developed using the `LinearRegression` class from the `sklearn.linear_model` module. The model is trained using the training data.
5. **Model Evaluation:** The trained model is evaluated using the testing data. Mean Squared Error (MSE) and R-squared (R2) scores are calculated to assess the model's performance.
6. **Visualization:** The actual house prices versus the predicted house prices are visualized using a scatter plot.

**Technologies Used:**
- Python: Programming language used for coding the project.
- Pandas: Library used for data manipulation and analysis.
- Scikit-learn: Library used for tasks such as data splitting, model development, and evaluation.
- Matplotlib: Library used for data visualization.

This project provides an introduction to regression modeling and prediction in the context of predicting house prices based on given features.
