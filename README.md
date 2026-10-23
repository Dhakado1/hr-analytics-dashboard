# HR Analytics & Employee Attrition Prediction System

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-lightgrey?logo=flask)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-green)

A complete Machine Learning and Flask-based web application for analyzing human resource metrics, forecasting employee attrition risk, and delivering actionable retention insights.

---

## 📌 Overview

This project analyzes the IBM HR Analytics Employee Attrition dataset to identify factors driving employee turnover and provides:
- **Interactive Web Dashboard**: Executive overview, KPI scorecards, risk explorer, and retention scenario simulator.
- **Attrition Risk Predictor**: Real-time prediction tool based on machine learning models.
- **Exploratory Data Analysis (EDA)**: Jupyter notebooks detailing data preparation, exploratory visualization, statistical testing, and model comparison.
- **Model Evaluation**: Comparison between Logistic Regression, Random Forest, and Gradient Boosting classifiers.

---

## 📁 Project Structure

```text
├── CODE/
│   ├── 01_Data_Preparation.ipynb       # Data cleaning & preprocessing
│   ├── 02_Data_Modeling.ipynb          # Model training & benchmarking
│   ├── 03_Data_Visualization.ipynb     # Exploratory visual analysis
│   └── 04_Statistical-Analysis.ipynb   # Statistical significance tests
├── data/                               # Cleaned dataset for the web application
├── DATASET/                            # Raw dataset
├── models/
│   ├── best_model.pkl                  # Serialized best-performing ML model
│   ├── feature_columns.pkl             # Encoded feature column list
│   └── metrics.json                    # Model evaluation metrics & ROC curves
├── static/
│   ├── css/                            # Dashboard styles
│   └── js/                             # Interactive charts & client-side logic
├── templates/                          # Jinja2 HTML templates
├── utils/
│   └── preprocess.py                   # Feature transformation helpers
├── app.py                              # Flask application backend
├── train_model.py                      # Standalone training script
└── requirements.txt                    # Project dependencies