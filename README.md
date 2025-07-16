#  Heart Disease Prediction using Machine Learning

This project aims to predict the likelihood of heart disease in patients using various machine learning models. The dataset includes several medical indicators like age, blood pressure, cholesterol, chest pain type, and more. The goal is to provide a reliable early-warning system for heart disease using predictive modeling.

---

##  Objective

To develop and compare machine learning models that can classify whether a patient is at risk of heart disease based on clinical and demographic attributes.

---

##  Key Steps

1. **Data Cleaning & Preprocessing**
   - Checked for missing/duplicate values
   - Scaled numerical features
   - Encoded categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Class distribution
   - Correlation heatmap
   - Feature-risk visualizations

3. **Feature Engineering**
   - Scaled and encoded relevant features
   - Identified most impactful predictors using feature importance

4. **Model Training**
   - Trained 7 ML models: Logistic Regression, KNN, SVM, Decision Tree, Random Forest, XGBoost, Naive Bayes

5. **Model Evaluation**
   - Evaluated using Accuracy, Precision, Recall, F1-Score, ROC-AUC
   - Confusion matrix and ROC curve for visualization

6. **Hyperparameter Tuning**
   - Used GridSearchCV and RandomizedSearchCV to optimize model parameters

7. **Implementation Context**
   - Real-world use in early risk detection, telemedicine, and clinical decision support

---

##  Results

| Model              | Accuracy |
|--------------------|----------|
| Random Forest      | ✅ High  |
| XGBoost            | ✅ High  |
| Logistic Regression| Moderate |
| Others             | Compared |

Random Forest and XGBoost performed the best in terms of accuracy and generalization.

---

## 🛠 Tools & Libraries Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

##  Project Structure

Heart_Disease_Prediction/
├── heart.csv
├── Heart_disease_prediction.ipynb
├── random_forest_model.pkl
└── README.md

