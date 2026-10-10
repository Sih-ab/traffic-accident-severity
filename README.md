# Traffic Accident Severity Prediction

## Project Overview
This project explores road traffic accident data and builds machine learning models to predict accident severity.

## Objectives
- Understand the dataset and its features.
- Explore accident patterns and missing values.
- Prepare data for machine learning.
- Train and evaluate classification models.
- Compare model performance across injury severity classes.

## Dataset
The dataset contains 8,210 records and 33 columns.

**Target variable:** `Accident_severity`

The target has three classes:
- Slight Injury
- Serious Injury
- Fatal injury

The dataset is not included in this repository.

## Tools and Technologies
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- VS Code

## Models
1. Random Forest Classifier
2. Logistic Regression

## Results

| Model | Accuracy | Macro F1-score |
|---|---:|---:|
| Random Forest | 86.7% | 0.431 |
| Logistic Regression | 73.7% | 0.527 |

Logistic Regression achieved a higher Macro F1-score, while Random Forest achieved higher accuracy.

Class imbalance remains a major challenge, particularly when predicting serious and fatal injuries.

## Project Structure

```text
traffic-accident-severity/
├── data/
├── notebooks/
│   └── 01_data_understanding.ipynb
├── .gitignore
└── README.md