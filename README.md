# Loan Approval Prediction – AI Final Project

This project explores the use of supervised machine learning models to predict whether an individual is likely to be approved for a loan based on key financial indicators.

## 📊 Problem Statement

The model estimates loan approval outcomes using:
- Annual income
- Number of credit inquiries
- Average monthly checking account balance
- Total outstanding debt

## 🧠 Techniques Used

The project compares several ensemble learning classifiers:
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

1. Data cleaning and feature engineering
2. Exploratory Data Analysis (EDA) and visualizations
3. Model training using multiple ensemble classifiers
4. Hyperparameter tuning via `GridSearchCV`
5. Model evaluation with classification reports and cross-validation

## 📈 Results

Each model was evaluated using:
- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrices

The best-performing model balanced high predictive accuracy with strong generalization across cross-validation folds.

## 🎓 Context

This project was completed as the final assignment for a graduate-level Artificial Intelligence course at Regis University. It focuses on applying core ML techniques to real-world structured data.

## 🚀 Future Work

- Add SHAP or feature importance visualizations
- Explore fairness metrics and bias analysis
- Deploy model as a REST API or Streamlit app

## 📁 File Structure

- `loan_prediction.ipynb` – Main analysis notebook
- `README.md` – Project overview and documentation

