# 📊 Customer Churn Prediction using Machine Learning

## About the Project

Customer churn is a major challenge for telecom companies because losing customers directly affects business growth. In this project, I built a machine learning model to predict whether a customer is likely to leave a telecom service based on customer information and the services they use.

The project follows a complete machine learning workflow, starting from data preprocessing and exploratory data analysis (EDA) to model training, evaluation, and saving the best-performing model.

---

## Dataset

This project uses the **Telco Customer Churn Dataset**, which contains customer information such as:

- Gender
- Senior Citizen
- Partner and Dependents
- Internet Service
- Contract Type
- Monthly Charges
- Total Charges
- Churn (Target Variable)

---

## Project Workflow

### 1. Data Exploration
- Loaded the dataset using Pandas.
- Explored the data using `.head()`, `.info()`, `.describe()`, and checked for missing values.

### 2. Data Preprocessing
- Removed unnecessary columns.
- Handled missing values.
- Converted data types.
- Encoded categorical variables.
- Split the dataset into features and target.

### 3. Exploratory Data Analysis (EDA)
Performed visual analysis to better understand the dataset, including:
- Customer churn distribution
- Numerical feature distributions
- Contract Type vs Churn
- Internet Service vs Churn
- Correlation analysis

### 4. Feature Scaling
Applied **StandardScaler** to scale numerical features before training machine learning models.

### 5. Model Training
Trained and compared the following classification models:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)

### 6. Hyperparameter Tuning
Improved model performance using **GridSearchCV**.

### 7. Model Evaluation
Compared all models using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 8. Model Saving
Saved the best-performing Logistic Regression model using **Joblib** for future use.

---

## Results

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **80.38%** |
| Random Forest | **79.10%** |
| K-Nearest Neighbors | **75.40%** |
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

## Repository Structure

```
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── customer_churn_model.pkl
└── README.md
```

---

## Future Improvements

- Deploy the model as a web application using Flask or FastAPI.
- Try advanced machine learning algorithms such as XGBoost.
- Improve prediction performance through additional feature engineering and tuning.

---

## Author

**Aleesha Shafique**

BS Information Technology Student | Aspiring AI/ML Engineer

GitHub: https://github.com/Aleesha-1

LinkedIn: https://www.linkedin.com/in/aleesha-shafique
