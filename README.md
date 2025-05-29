# AIML_Internship_Task3
# House Price Prediction using Linear Regression

This task demonstrates a complete pipeline for predicting house prices using the **Linear Regression** model on the Kaggle Housing dataset.

## Steps Performed

### 1. Import and Load the Dataset
- Imported necessary libraries such as `pandas`, `matplotlib`, `sklearn`.
- Loaded the dataset into a pandas DataFrame.

### 2. Data Preprocessing
- Identified and handled **categorical variables** using `OneHotEncoder`.
- Applied **standardization** on important numeric features like `price` and `area` using `StandardScaler`.
- **Removed outliers** using the box-plot method to improve model performance.

### 3. Train-Test Split
- Split the processed data into `X_train`, `X_test`, `y_train`, `y_test` using `train_test_split` with `random_state=42`.

### 4. Model Training
- Trained a **Linear Regression** model using `sklearn.linear_model.LinearRegression`.

### 5. Model Evaluation
- Evaluated the model using:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **R² Score**
- Also performed **inverse transformation** on the standardized predictions to interpret results in original units.

### 6. Visualization
- Plotted **Actual vs Predicted Prices** using a scatter plot and a reference line to visually inspect prediction accuracy.

### 7. Coefficient Interpretation
- Extracted model coefficients to understand the impact of each feature on price prediction.
