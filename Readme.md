# 📊 Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses. This project uses Machine Learning to predict whether a customer is likely to leave a telecom service based on customer demographics, account details, and service usage.

The project follows a complete machine learning workflow including data preprocessing, exploratory data analysis (EDA), feature encoding, feature scaling, model training, hyperparameter tuning, and model evaluation.

---

## 🎯 Objective

The objective of this project is to build and compare multiple machine learning models to accurately predict customer churn and identify the best-performing classifier.

---

## 📂 Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains customer information such as:

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
- Churn (Target Variable)

---

## ⚙️ Project Workflow

### 1. Data Loading
- Imported required Python libraries.
- Loaded the Telco Customer Churn dataset.

### 2. Data Exploration
- Checked dataset shape, information, descriptive statistics, and missing values.

### 3. Data Preprocessing
- Removed unnecessary columns.
- Handled missing values.
- Converted data types.
- Encoded categorical variables.
- Split features and target variable.

### 4. Exploratory Data Analysis (EDA)
- Churn distribution
- Numerical feature distributions
- Contract Type vs Churn
- Internet Service vs Churn
- Correlation analysis

### 5. Feature Scaling
- Applied StandardScaler to numerical features.

### 6. Model Training
The following Machine Learning models were trained:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)

### 7. Hyperparameter Tuning
- Improved model performance using GridSearchCV.

### 8. Model Evaluation
Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 9. Model Saving
- Saved the trained Logistic Regression model using Joblib.

---

## 📈 Results

| Model | Accuracy |
|---------|----------|
| Logistic Regression | **80.38%** |
| Decision Tree | **73.60%** |
| Random Forest | **79.10%** |
| K-Nearest Neighbors | **75.40%** |

**Best Performing Model:** Logistic Regression

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── customer_churn_model.pkl
└── README.md
```

---

## 🚀 Future Improvements

- Deploy the model using Flask or FastAPI.
- Build an interactive web application.
- Experiment with XGBoost and LightGBM.
- Perform feature selection for improved performance.

---

## 👩‍💻 Author

**Aleesha Shafique**

BS Information Technology Student

Aspiring AI/ML Engineer

GitHub: https://github.com/Aleesha-1

LinkedIn: https://www.linkedin.com/in/aleesha-shafique/
