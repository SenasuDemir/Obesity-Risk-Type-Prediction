# Obesity Risk Type Prediction 🏥🍏

## 📚 Introduction
Obesity is a major health concern worldwide, linked to various chronic diseases such as diabetes, hypertension, and cardiovascular disorders. Predicting obesity levels based on lifestyle and physiological factors can help in early intervention and health awareness.

This project applies machine learning techniques to classify individuals into different obesity categories based on various personal and lifestyle attributes. 

## 🎯 Aim of the Project
The goal of this project is to develop a classification model that can accurately predict the obesity level of individuals using features such as:
- Age
- Weight
- Height
- Eating habits
- Physical activity
- Mode of transportation

We will analyze the dataset, perform feature engineering, apply different classification algorithms, and compare their performance to determine the best model. 

## 📊 Dataset Explanation
The dataset contains various personal, behavioral, and physiological features related to obesity classification. Below is a description of the columns in the dataset:

| **Column Name**                   | **Description** |
|------------------------------------|-----------------|
| `id`                               | Unique identifier for each individual. |
| `Gender`                           | The gender of the individual (Male/Female). |
| `Age`                              | Age of the person in years. |
| `Height`                           | Height of the individual in meters. |
| `Weight`                           | Weight of the individual in kilograms. |
| `family_history_with_overweight`   | Whether the individual has a family history of overweight (yes/no). |
| `FAVC`                             | Frequent consumption of high-calorie food (yes/no). |
| `FCVC`                             | Frequency of vegetable consumption (scale from 1 to 3). |
| `NCP`                              | Number of main meals consumed per day. |
| `CAEC`                             | Frequency of eating between meals (Sometimes, Frequently, Always, No). |
| `SMOKE`                            | Whether the person smokes (yes/no). |
| `CH2O`                             | Daily water consumption in liters. |
| `SCC`                              | Whether the individual monitors calorie consumption (yes/no). |
| `FAF`                              | Physical activity frequency (scale from 0 to 3). |
| `TUE`                              | Time spent using technology devices (scale from 0 to 2). |
| `CALC`                             | Alcohol consumption frequency (Sometimes, Frequently, Always, No). |
| `MTRANS`                           | Mode of transportation used (Public Transportation, Automobile, Walking, etc.). |
| `NObeyesdad`                       | Target variable: Obesity classification level (e.g., Normal Weight, Obesity Type I, Overweight Level II, etc.). |

## 🔬 Models & Accuracy Score
The following models were evaluated, and their accuracy scores were obtained:

- **LightGBM Classifier**: 90.51% 🏆
- **Gradient Boosting Classifier**: 90.44% 🔥
- **Random Forest Classifier**: 88.75% 🌲
- **Decision Tree Classifier**: 84.49% 🌳
- **KNeighbors Classifier**: 84.18% 🧑‍🤝‍🧑
- **Logistic Regression**: 69.20% ⚖️
- **Gaussian NB**: 61.15% 📉
- **Bernoulli NB**: 56.36% ❌

## 🏁 Conclusion
Based on the accuracy scores, **LightGBM Classifier** emerged as the best-performing model with an accuracy of 90.51%, followed closely by **Gradient Boosting Classifier** (90.44%). These models outperformed others like Logistic Regression and Naive Bayes classifiers, which had lower accuracy.

The **LightGBM model** is identified as the optimal choice for predicting obesity levels in this dataset. Future work can focus on hyperparameter tuning, feature engineering, and cross-validation to further enhance model performance.

## 🔗 Kaggle Notebook
You can find the original notebook on Kaggle: [Obesity Risk Type Prediction Notebook](https://www.kaggle.com/code/senasudemir/obesity-risk-type-prediction?scriptVersionId=222688550)
