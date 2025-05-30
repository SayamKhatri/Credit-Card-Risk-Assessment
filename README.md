# Credit Card Default Risk Assessment 

This project analyzes and predicts the likelihood of default by credit card clients. The goal is to build reliable classification models and compare their performance using various evaluation metrics like AUC and accuracy.



# Models Implemented
- **Logistic Regression** (baseline)
- **XGBoost Classifier** (with RandomizedSearchCV)
- **Neural Network** using TensorFlow/Keras

# Evaluation Metrics
- Accuracy
- AUC (Area Under Curve)
- Confusion Matrix
- Classification Report



# Model Comparison Summary

| Model              | Accuracy | AUC   | Notes                           |
|-------------------|----------|-------|----------------------------------|
| Logistic Regression | ~0.81   | ~0.74 | Strong baseline, class imbalance handling |
| XGBoost            | ~0.83     | ~0.83   | Tuned with RandomSearchCV       |
| Neural Network     | ~0.80   | ~0.74 | Well-regularized with dropout   |


