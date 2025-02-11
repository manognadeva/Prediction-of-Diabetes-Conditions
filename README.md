# Prediction-of-Diabetes-Conditions

This repository contains a machine learning project aimed at predicting the likelihood of diabetes based on various health-related features and identifying the highest risk factors contributing to diabetes. The project involves data preprocessing, exploratory data analysis, dimension reduction, model development, and evaluation.

## Project Overview

The goal of this project is to build a predictive model that identifies individuals at risk of diabetes using health indicators such as BMI, physical activity, smoking status, and more. The dataset includes structured data with features that influence diabetes risk and a target variable indicating the presence or absence of diabetes.

## Features in the Dataset

The dataset includes features like:

- **HighBP**: High blood pressure
- **HighChol**: High cholesterol
- **BMI**: Body Mass Index
- **Smoker**: Smoking status
- **PhysActivity**: Physical activity level
- **Fruits**: Fruit consumption
- **Age**: Age group
- **Education**: Education level
- **Income**: Income level

The target variable is `Diabetes_binary`, which indicates whether an individual has diabetes (1) or not (0).

## Key Steps in the Project

1. **Data Preprocessing**:
   - Handled missing values.
   - Encoded categorical variables.
   - Scaled numerical features for model compatibility.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized feature distributions and correlations.
   - Identified key factors influencing diabetes risk.

3.  **Dimensionality Reduction**:
   - Applied Principal Component Analysis (PCA) to reduce dataset dimensionality while retaining variance.

4. **Model Development**:
   - Built multiple machine learning models:
     - Random Forest Classifier
     - KNN Classifier
     - Decision Trees
   - Performed hyperparameter tuning to optimize model performance.

5. **Model Evaluation**:
   - Evaluated models using metrics such as accuracy, precision, recall, and F1-score.
   - Compared performance across models to select the best one.

6. **Feature Importance Analysis**:
   - Identified the most significant features contributing to diabetes prediction.

## How to Run the Project

1. Clone this repository to your local machine.
2. Ensure you have Python installed along with the required libraries (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`).
3. Open the Jupyter Notebook file (`Code.ipynb`).
4. Run all cells sequentially to reproduce the analysis and results.

## Results

The project demonstrates how machine learning can be used to predict health outcomes effectively. The best-performing model provides actionable insights into diabetes risk factors, which can assist healthcare professionals in early intervention strategies.

## Future Enhancements

- Incorporate additional datasets for improved generalization.
- Explore deep learning techniques for better prediction accuracy.
- Develop a user-friendly interface for real-time diabetes risk prediction.
