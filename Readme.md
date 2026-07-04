# Customer Churn Prediction using Machine Learning

## About the Project

Customer churn is a major challenge for subscription-based businesses because losing customers directly impacts revenue and growth. In this project, I built a machine learning model to predict whether a telecom customer is likely to leave the service based on customer demographics, account information, and subscribed services.

The project follows a complete machine learning workflow, including data understanding, preprocessing, exploratory data analysis (EDA), feature engineering, feature scaling, model training, hyperparameter tuning, evaluation, and saving the best-performing model.

---

## Dataset

This project uses the **Telco Customer Churn Dataset**, which contains customer information such as:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Contract Type
- Monthly Charges
- Total Charges

**Target Variable:** Churn (Yes / No)

---

## Project Workflow

### 1. Data Understanding

- Loaded the dataset using Pandas.
- Explored the dataset using `.head()`, `.info()`, `.describe()`, and checked for missing values.
- Examined the dataset structure, data types, and summary statistics.

### 2. Data Preprocessing

- Removed unnecessary columns.
- Handled missing values.
- Converted data types where required.
- Encoded categorical variables.
- Split the dataset into input features and target variable.

### 3. Exploratory Data Analysis (EDA)

Performed exploratory analysis to better understand customer behavior by analyzing:

- Churn distribution
- Numerical feature distributions
- Contract Type vs Churn
- Internet Service vs Churn
- Correlation between numerical features

### 4. Feature Scaling

- Applied **StandardScaler** to normalize numerical features before training the models.

### 5. Model Development

Built and compared the following machine learning models:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)

### 6. Hyperparameter Tuning

- Improved model performance using **GridSearchCV**.

### 7. Model Evaluation

Compared all models using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 8. Model Saving

- Saved the best-performing Logistic Regression model using **Joblib** for future use.

---

## Results

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **80.38%** |
| Random Forest | **79.10%** |
| K-Nearest Neighbors (KNN) | **75.40%** |
| Decision Tree | **73.60%** |

**Best Performing Model:** Logistic Regression

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## Key Learning

Through this project, I gained practical experience in building an end-to-end machine learning pipeline. I learned how data preprocessing, exploratory data analysis, feature engineering, and feature scaling influence model performance. I also understood the importance of comparing multiple algorithms, tuning hyperparameters with GridSearchCV, and evaluating classification models using different performance metrics before selecting the best model.

---

## Author

**Aleesha Shafique**

BS Information Technology Student | Aspiring AI/ML Engineer

- GitHub: https://github.com/Aleesha-1
- LinkedIn: https://www.linkedin.com/in/aleesha-shafique
