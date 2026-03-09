# Lung Cancer Prediction Project

This project leverages machine learning to predict the likelihood of lung cancer in individuals based on survey data. By analyzing several lifestyle and health factors, the models aim to identify high-risk individuals for early intervention.

## Table of Contents

* [Overview](https://www.google.com/search?q=%23overview)
* [Dataset](https://www.google.com/search?q=%23dataset)
* [Installation](https://www.google.com/search?q=%23installation)
* [Workflow](https://www.google.com/search?q=%23workflow)
* [Models Used](https://www.google.com/search?q=%23models-used)
* [Results](https://www.google.com/search?q=%23results)
* [Technologies Used](https://www.google.com/search?q=%23technologies-used)

## Overview

Lung cancer is one of the most prevalent and deadly forms of cancer. Early detection is critical for improving survival rates. This project implements a diagnostic tool using classification algorithms to predict cancer presence (`YES`/`NO`) based on features like smoking habits, age, and various symptoms.

## Dataset

The dataset consists of **309 entries** and **16 attributes**. It includes demographic information and several clinical symptoms.

* **Target Variable:** `LUNG_CANCER` (YES/NO)
* **Key Features:**
* **Demographics:** Gender, Age.
* **Behavioral:** Smoking, Alcohol Consuming.
* **Clinical Symptoms:** Yellow Fingers, Anxiety, Peer Pressure, Chronic Disease, Fatigue, Allergy, Wheezing, Coughing, Shortness of Breath, Swallowing Difficulty, Chest Pain.



## Installation

To run this project locally, ensure you have Python installed, then install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost

```

## Workflow

1. **Exploratory Data Analysis (EDA):** Visualizing the distribution of the target variable and feature correlations.
2. **Data Preprocessing:**
* Encoding categorical variables using `LabelEncoder`.
* Splitting data into training and testing sets (typically 80/20).


3. **Model Training:** Training multiple classification models to compare performance.
4. **Evaluation:** Metrics used include Accuracy Score, Confusion Matrix, and Classification Report (Precision, Recall, F1-Score).

## Models Used

The following machine learning algorithms were implemented and compared:

* **Logistic Regression:** A baseline linear model for binary classification.
* **Random Forest Classifier:** An ensemble learning method using multiple decision trees.
* **XGBoost Classifier:** A powerful gradient boosting algorithm optimized for performance.

## Results

* The dataset shows a mean age of approximately **62.6 years**, with ages ranging from 21 to 87.
* The models were evaluated using confusion matrices to identify the balance between true positives and false negatives.
*(Note: You can add specific accuracy scores here based on your final notebook execution.)*

## Technologies Used

* **Languages:** Python
* **Libraries:** Pandas, NumPy (Data Manipulation), Matplotlib, Seaborn (Visualization), Scikit-Learn (Machine Learning), XGBoost (Advanced Gradient Boosting).


