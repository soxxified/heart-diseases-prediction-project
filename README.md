# heart-diseases-prediction-project
classifies which model is best suitable to predict heart diseases based on the dataset using python and google colab
# Heart Disease Prediction Using Machine Learning

## Project Overview

This project aims to predict the presence of heart disease using Machine Learning techniques. The analysis was performed using Python in Google Colab and includes data preprocessing, feature engineering, model training, evaluation, and comparison of multiple classification algorithms.

## Dataset

The dataset contains medical attributes related to heart disease diagnosis, including:

* Age
* Sex
* Chest Pain Type (cp)
* Resting Blood Pressure (trestbps)
* Cholesterol (chol)
* Fasting Blood Sugar (fbs)
* Resting ECG Results (restecg)
* Maximum Heart Rate Achieved (thalach)
* Exercise Induced Angina (exang)
* ST Depression (oldpeak)
* Slope of Peak Exercise ST Segment (slope)
* Number of Major Vessels (ca)
* Thalassemia (thal)
* Target (Heart Disease Presence)

## Project Objectives

* Explore and understand the dataset
* Perform feature engineering using correlation analysis
* Train multiple machine learning models
* Compare model performance using classification metrics
* Identify the best-performing model for heart disease prediction

## Tools and Libraries Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Data Preprocessing

* Checked for missing values
* Verified data types
* Confirmed dataset quality
* Split dataset into training and testing sets (80:20 ratio)
* Applied feature selection using correlation analysis

## Feature Engineering

Correlation analysis was performed to identify features most strongly related to heart disease prediction. Highly relevant features were selected to improve model performance and reduce noise.

## Machine Learning Models

The following classification algorithms were implemented:

1. Logistic Regression
2. Random Forest Classifier
3. K-Nearest Neighbors (KNN)

## Model Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score

A comparison table was created to identify the best-performing model.

## Results

The models were trained and evaluated on the testing dataset. Random Forest achieved the highest overall performance and demonstrated strong predictive capability for heart disease classification.

## Visualizations

The project includes:

* Correlation Heatmap
* Feature Importance Analysis
* Confusion Matrix
* Performance Comparison Table

## Key Findings

1. Chest pain type, maximum heart rate, and ST slope were among the most influential predictors.
2. Correlation analysis helped identify the most relevant features.
3. Random Forest outperformed Logistic Regression and KNN.
4. The confusion matrix showed strong classification performance.
5. Machine learning can effectively support heart disease prediction and early risk assessment.

## Repository Contents

* `heart_disease_prediction.ipynb` — Complete Google Colab notebook
* `README.md` — Project documentation

## Author

Saksham Rathore

## License

This project is intended for educational and academic purposes.
## dataset source
kaggle
