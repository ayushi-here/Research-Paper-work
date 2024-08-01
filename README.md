# 📚Research Paper:Predicting Student Dropout Rates🎓

## Overview
This research delves into predicting student dropout rates using various supervised machine learning models. The aim is to identify which models offer the best performance for early intervention strategies in education.

## 🛠️ Methodology
- **Data Split:** 70% training, 30% testing
- **Metric:** Accuracy, calculated as:
  
  \[ \text{Accuracy} = \frac{\text{Number of Correct Predictions}}{\text{Total Number of Predictions}} \]

## 📊 Results

### Dataset Summary

| Dataset | Dropout (0) | Successful (1) | Total |
|---------|-------------|----------------|-------|
| Train   | 101         | 423            | 524   |
| Test    | 43          | 186            | 229   |
| **Sum** | **144**     | **609**        | **753** |

### Model Performance

| Model                                  | Accuracy (%) |
|----------------------------------------|--------------|
| Decision Tree                          | 69.38        |
| Random Forest                          | 80.56        |
| Logistic Regression                    | 78.08        |
| K-Nearest Neighbors (KNN)               | 69.38        |
| AdaBoost                               | 77.18        |
| XGBoost                                | 79.89        |
| Support Vector Machine (SVM)            | 77.06        |
| **Ensemble (Soft Voting)**              | **82.15**    |
| **Ensemble (Hard Voting)**              | **81.02**    |

## 🔍 Insights
- **Top Performer:** Gradient Boosting Machine with 82.15% accuracy 🎯
- **Best Ensemble Method:** Soft Voting 🤖
- **Least Effective:** Decision Tree and Logistic Regression (69.38%) 🛠️

## 📝 Conclusion
Ensemble methods, particularly Soft Voting, are highly effective in predicting student dropout rates. This can aid in developing early intervention strategies.
