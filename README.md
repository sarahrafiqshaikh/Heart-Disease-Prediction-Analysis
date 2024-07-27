# Heart-Disease-Prediction-Analysis
This project analyzes a heart disease dataset to predict the presence of heart disease in patients using machine learning techniques.

Here's a README based on the provided notebook content:

# Heart Disease Prediction Analysis

This project analyzes a heart disease dataset to predict the presence of heart disease in patients using machine learning techniques.

## Dataset

The dataset is from the UCI Machine Learning Repository and contains various features related to heart health. It can be downloaded from Kaggle: [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

## Features

The dataset includes the following features:
- age: Age in years
- sex: Sex (1 = male; 0 = female)
- cp: Chest pain type
- trestbps: Resting blood pressure
- chol: Serum cholesterol
- fbs: Fasting blood sugar
- restecg: Resting electrocardiographic results
- thalach: Maximum heart rate achieved
- exang: Exercise induced angina
- oldpeak: ST depression induced by exercise relative to rest
- slope: The slope of the peak exercise ST segment
- ca: Number of major vessels colored by fluoroscopy
- thal: Thalassemia
- target: Presence of heart disease (0 = no, 1 = yes)

## Analysis Steps

1. Data Preprocessing and Cleansing
2. Exploratory Data Analysis (EDA)
3. Outlier Detection and Handling
4. Feature Selection and Engineering
5. Model Training (Random Forest Classifier)
6. Hyperparameter Tuning
7. Model Evaluation

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage

1. Clone the repository
2. Install the required packages
3. Run the Jupyter notebook

## Results

The analysis includes:
- Correlation heatmap
- Distribution of heart disease in the dataset
- Box plots for numerical features
- Feature importance visualization
- Confusion matrix
- ROC curve

The Random Forest Classifier was used for prediction, with hyperparameter tuning performed using GridSearchCV.

## Author
Sarah Rafiq Shaikh

## Acknowledgements

Dataset source: UCI Machine Learning Repository
