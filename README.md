#  Heart Disease Prediction

Predicting the presence of heart disease using machine learning by analyzing patient clinical data.

##  Project Overview

This project builds and compares multiple classification models to predict heart disease. It follows a complete machine learning pipeline:

1. **Data preprocessing** (cleanup, encoding, scaling)
2. **Model training** with 7 algorithms:
   - Logistic Regression  
   - K‑Nearest Neighbors  
   - Support Vector Machine (RBF kernel)  
   - Decision Tree  
   - Random Forest  
   - XGBoost  
   - Naive Bayes
3. **Hyperparameter tuning** using `GridSearchCV` & `RandomizedSearchCV`
4. **Model evaluation** based on:
   - Accuracy (training & testing)
   - ROC-AUC and ROC curve plots
   - Confusion matrices
5. **Best model selection** (usually Random Forest)
6. **Model export** using `pickle` for future use

---

