# 🏠 Housing Price Prediction - Linear Regression

This project is part of the AI & ML Internship Program and focuses on implementing and understanding **linear regression** using the popular **Housing Price Prediction** dataset. The aim is to explore how well we can predict housing prices based on features such as area, bedrooms, and location characteristics.

---

## 🎯 Objective

To build and evaluate a linear regression model to predict house prices based on multiple features, and gain hands-on experience in:

- Regression modeling using `scikit-learn`
- Evaluating model performance (MAE, MSE, R²)
- Understanding regression assumptions and coefficients
- Visualizing predictions

---

## 📊 Dataset

- **Source:** [Kaggle - Housing Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
- **File:** `Housing.csv`
- **Attributes Include:**
  - `area`, `bedrooms`, `bathrooms`, `stories`, `mainroad`, `furnishingstatus`, etc.
  - **Target variable:** `price`

---

## 🛠 Tools & Libraries Used

- **Python**
- **Pandas**, **NumPy** — Data handling
- **Matplotlib**, **Seaborn** — Data visualization
- **Scikit-learn** — Machine learning

---

## 🧪 Steps Performed

### 1. Data Exploration
- Displayed basic statistics using `.describe()`, `.info()`
- Visualized key numeric features and distributions

### 2. Data Preprocessing
- Encoded categorical variables using one-hot encoding
- Checked for and handled missing values

### 3. Splitting Dataset
- Split into **80% training** and **20% testing** using `train_test_split`

### 4. Model Training
- Applied **Multiple Linear Regression** using `LinearRegression()`
- Trained on training data and made predictions on the test set

### 5. Evaluation Metrics
- **MAE** (Mean Absolute Error)
- **MSE** (Mean Squared Error)
- **RMSE** (Root Mean Squared Error)
- **R² Score** (Coefficient of Determination)

### 6. Interpretation
- Interpreted the coefficients to understand the influence of each feature on house price

### 7. Visualization
- Plotted regression line for simple models
- Compared actual vs predicted values using scatter plots

---

## 🖼️ Screenshots

### 📍 Actual vs Predicted Price (Scatter Plot)
![regression_plots](https://github.com/user-attachments/assets/944a1f2b-36af-480c-b127-cb8b9f1ca118)

---

## 🧠 Key Learnings

- Linear regression works best when assumptions (linearity, homoscedasticity, no multicollinearity, normality) are met
- Categorical features must be encoded
- R² score tells how much variance in the target variable is explained by the model
- Evaluation metrics help compare multiple regression models

---


