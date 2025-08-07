 Linear Regression - Housing Price Prediction

 Task Overview

This project is part of the AI & ML Internship and focuses on implementing **Simple and Multiple Linear Regression** using Python and Scikit-learn to predict house prices based on features such as square footage, number of bedrooms/bathrooms, neighborhood, and year built.

 Objective

- Understand and implement linear regression
- Evaluate model performance using metrics: MAE, MSE, and R²
- Interpret model coefficients
- Visualize model predictions

Dataset

- Dataset used: Housing Price Prediction
- Source: [Kaggle - Housing Price Prediction]
- Features:
  - `SquareFeet`: Area of the house
  - `Bedrooms`: Number of bedrooms
  - `Bathrooms`: Number of bathrooms
  - `Neighborhood`: Categorical (Urban, Suburb, Rural)
  - `YearBuilt`: Year of construction
  - `Price`: Target variable

Technologies Used

- Python
- Pandas
- Matplotlib & Seaborn
- Scikit-learn

---

 Steps Performed

1. Data Preprocessing
   - Handled categorical data using `pd.get_dummies()`
   - Checked for missing values

2. Train-Test Split
   - Used `train_test_split()` from Scikit-learn

3. Model Training
   - Fitted `LinearRegression()` on training data

4. Model Evaluation
   - Calculated Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score

5. Visualization
   - Plotted Actual vs Predicted prices
   - Visualized residuals



