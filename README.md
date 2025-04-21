# Loan Approval Prediction – AI Final Project

This project explores supervised machine learning techniques to predict whether an individual will be approved for a loan, based on key financial and behavioral features.

## 📊 Problem Overview

The task is to estimate loan approval outcomes using:
- Annual income
- Number of credit inquiries
- Average monthly balance in a checking account
- Outstanding debt

## 🧠 Machine Learning Models

We applied and compared the following ensemble classifiers:
- Random Forest
- AdaBoost
- Gradient Boosting

## 🛠️ Tools & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## ⚙️ Workflow

1. **Data Preprocessing**
   - Cleaned and transformed financial data
   - Normalized features and handled missing values

2. **Exploratory Data Analysis**
   - Visualized distributions, feature correlations, and class balance

3. **Model Training & Evaluation**
   - Trained multiple ensemble classifiers using `train_test_split`
   - Performed hyperparameter tuning with `GridSearchCV`
   - Evaluated using classification reports and cross-validation

## 📈 Results

Each model was assessed using:
- Accuracy
- Precision, Recall, and F1-Score
- Confusion Matrix

The models achieved solid performance, with ensemble methods showing strong generalization across the test data.

## 🎓 Academic Context

This project was completed as the final assignment for the Artificial Intelligence course in the M.S. Software Engineering program at Regis University. It demonstrates practical machine learning skills applied to a realistic financial decision-making problem.

## 🚀 Future Improvements

- Incorporate SHAP or feature importance visualizations
- Deploy as a Streamlit app or API
- Expand dataset and explore fairness metrics

## 📁 Files

- `ICS-352-AI-Final-Project.ipynb` – Main analysis notebook
- `README.md` – Project documentation
