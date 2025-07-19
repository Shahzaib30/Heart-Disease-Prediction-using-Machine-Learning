# Heart-Disease-Prediction-using-Machine-Learning
This project is part of my Data Science Internship with Digital Empowerment Network (July 2025). It predicts heart disease using three supervised ML models:
- Logistic Regression
- Decision Tree
- Random Forest

## 🔧 Tools Used

- Python (Pandas, Scikit-Learn, imbalanced-learn)
- SMOTE for class balancing
- GridSearchCV for hyperparameter tuning
- Joblib for model export

## 🧠 Model Performance

| Model               | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|--------------------|----------|-----------|--------|----------|---------|
| Logistic Regression| 0.82     | 0.83      | 0.79   | 0.80     | 0.88    |
| Decision Tree      | 0.74     | 0.75      | 0.72   | 0.72     | 0.78    |
| Random Forest      | 0.85     | 0.85      | 0.82   | 0.84     | 0.91    |

## 📁 Files

- `model_training.ipynb`: Training + Evaluation + Cross-validation
- `logistic_regression.joblib`
- `decision_tree.joblib`
- `random_forest.joblib`
- `scaler.joblib`

## 🚀 Upcoming

- Streamlit Web App for live predictions.
