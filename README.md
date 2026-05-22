## AI-AGRI Crop Risk Assessment using Machine Learning

An AI-based agricultural risk assessment project designed to analyze crop-selection risks under climate variability conditions using supervised machine learning techniques.

This project demonstrates how agricultural datasets, feature engineering, and Random Forest classification can be used to predict crop risk categories based on environmental and farming-related parameters.

## Project Objective

The main objective of this project is to predict agricultural crop-selection risks using AI and machine learning by analyzing factors such as:

Rainfall
Soil moisture
Irrigation delay
Temperature
Fertilizer usage
Climate variability
Pest risk

The project focuses on understanding how agricultural decisions influence crop-risk outcomes and how AI can assist in data-driven farming practices.

## Problem Statement

Traditional agricultural decision-making often relies on:

Rule-of-thumb fertilizer practices
Delayed irrigation responses
Manual crop selection decisions

These practices may result in:

Yield loss
Water mismanagement
Climate vulnerability
Increased agricultural risk

This project explores how machine learning can help model and predict these risks using structured agricultural datasets.

## Technologies Used
Technology	Purpose
Python	Programming Language
Google Colab	Model Development Environment
Pandas	Data Processing
NumPy	Numerical Operations
Scikit-learn	Machine Learning
Matplotlib	Data Visualization
Excel / Google Sheets	Dataset Preparation
GitHub	Version Control & Hosting
Machine Learning Approach
Learning Paradigm

Supervised Learning

Model Used

Random Forest Classifier

The Random Forest model was selected because:

It performs well on structured datasets
Handles multiple agricultural features effectively
Reduces overfitting
Provides feature importance analysis
Dataset Features

The dataset contains engineered agricultural features including:

Feature
Crop Type
Rainfall (mm)
Temperature (°C)
Soil Moisture (%)
Irrigation Delay (Days)
Fertilizer Usage
Humidity (%)
Climate Risk
Water Availability Score
Pest Risk Level
Predicted Risk
Workflow
Dataset Preparation
        ↓
Feature Engineering
        ↓
Data Preprocessing
        ↓
Model Training
        ↓
Prediction Generation
        ↓
Accuracy Evaluation
        ↓
Feature Importance Analysis
Experimental Modifications

The following experiments were performed:

Modified irrigation delay values
Added climate-risk categories
Adjusted fertilizer usage patterns
Compared prediction outputs after feature changes

These experiments helped analyze model sensitivity and feature importance.

Results

The Random Forest model demonstrated strong agricultural risk prediction performance.

Sample Accuracy
Model	Accuracy
Logistic Regression	78%
Decision Tree	84%
Random Forest	91%
Key Observations
Lower soil moisture increased crop-risk probability.
Higher irrigation delay strongly influenced prediction outcomes.
Climate-related features improved prediction quality.
Feature engineering significantly improved model behavior.
Screenshots Included

The project contains:

Dataset preview
Training process logs
Prediction result tables
Accuracy outputs
Confusion matrix
Feature importance graph
Project Structure
AI-AGRI-Crop-Risk-Assessment/
│
├── AI_AGRI_Project_Report_Barnik_Basu.pdf
├── crop_selection_risk_dataset.xlsx
├── AI_AGRI_Project.ipynb
├── README.md
│
└── Screenshots/
    ├── dataset_preview.png
    ├── prediction_table.png
    ├── accuracy_score.png
    ├── confusion_matrix.png
    └── feature_importance_graph.png
Google Colab Notebook

Add your Colab notebook link here:

https://colab.research.google.com/drive/XXXXXXXXXXXX
GitHub Repository

Repository Link:

AI-AGRI-Crop-Risk-Assessment Repository

Future Improvements

Possible future enhancements include:

Real-time weather API integration
IoT-based soil moisture monitoring
Smart irrigation recommendations
Satellite-based agricultural analysis
Deep learning approaches for crop prediction
Conclusion

This project demonstrates how AI and machine learning can support agricultural decision-making under climate variability conditions.

The project highlights the importance of:

Feature engineering
Agricultural data analysis
AI-driven prediction systems
Experimental problem-solving

It also emphasizes that meaningful AI applications are built not only through algorithms, but through understanding real-world problems deeply.

Author

Barnik Basu
B.Tech CSE — IIIT Kalyani
