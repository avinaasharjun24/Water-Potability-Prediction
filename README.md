# Water Potability Prediction Using ML

## Project Overview
Access to safe drinking water is a major public health concern. This project aims to develop a machine learning-based classification system to predict whether water is potable or not based on physicochemical properties.

Multiple machine learning models were implemented, optimized, and evaluated to identify the most reliable classifier for water potability prediction.

---

## Dataset
- Source: Water Potability Dataset
- Target Variable: `Potability`
  - 1 → Potable
  - 0 → Not Potable
- The dataset contains missing values and class imbalance, which were handled during preprocessing.

---

## Methodology
1. Data loading and exploration
2. Missing value imputation (median strategy)
3. Feature scaling using StandardScaler
4. Class imbalance handling using SMOTE
5. Model training and comparison:
   - Support Vector Classifier (SVC)
   - Random Forest
   - K-Nearest Neighbors (KNN)
   - Decision Tree
   - XGBoost
6. Hyperparameter tuning using GridSearchCV and RandomizedSearchCV
7. Model evaluation using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix
   - ROC Curve and AUC
8. Feature importance analysis using:
   - Native importance (tree-based models)
   - Permutation importance (SVC and KNN)

---

## Results
- Hyperparameter tuning significantly improved model performance.
- Ensemble and boosting models achieved superior F1-scores and AUC values.
- Feature importance analysis provided insights into influential water quality parameters.

---

## Conclusion
The project demonstrates that machine learning techniques can effectively predict water potability. The final tuned model provides a reliable and interpretable solution suitable for real-world water quality assessment.
