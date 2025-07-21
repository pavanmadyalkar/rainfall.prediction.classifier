# 🌧️ Rainfall Prediction Classifier

This project builds a machine learning classifier to predict whether it will rain tomorrow using historical weather data. Two models are implemented and compared: **Random Forest** and **Logistic Regression**.

## 📌 Project Overview

Rainfall prediction is essential for agriculture, disaster preparedness, and daily planning. This project uses weather data to train classification models that predict the likelihood of rainfall the next day.

## 🧰 Technologies Used

- Python 3.1
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Seaborn

## 📂 Dataset

The dataset includes features such as temperature, humidity, wind speed, and atmospheric pressure. The target variable is `RainTomorrow` (Yes/No).

## ⚙️ Models Used

### 1. Logistic Regression
- A linear model used as a baseline.
- Interpretable and efficient.
- Evaluated using accuracy, precision, recall.

### 2. Random Forest Classifier
- An ensemble model of decision trees.
- Handles non-linear relationships and feature interactions.
- Typically outperforms simpler models on complex datasets.

## 📊 Evaluation Metrics

- Accuracy
- Precision, Recall, F1-Score
- Confusion Matrix

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/rainfall-prediction.git
   cd rainfall-prediction
   ```
2. Run RainFall_prediction_classifier.ipynb
