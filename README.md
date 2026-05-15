# Explainable Clinical Risk Prediction for Heart Disease

## Project Overview

This project investigates explainable clinical risk prediction for heart disease using statistical and machine learning approaches.

The study compares Logistic Regression and Random Forest models for cardiovascular disease prediction while integrating Explainable AI (XAI) techniques using SHAP (SHapley Additive exPlanations) to improve interpretability and transparency in healthcare AI systems.

The objective is to explore how interpretable machine learning can support trustworthy AI-assisted clinical decision-support systems.

---

## Dataset

The project uses the UCI Heart Disease dataset containing clinical and physiological variables associated with cardiovascular disease prediction.

### Key Features
- Age
- Chest Pain Type (`cp`)
- Cholesterol (`chol`)
- Maximum Heart Rate (`thalach`)
- ST Depression (`oldpeak`)
- Number of Major Vessels (`ca`)
- Thalassemia (`thal`)
- Exercise-Induced Angina (`exang`)

### Target Variable
- `0` → No Heart Disease
- `1` → Presence of Heart Disease

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SHAP

---

## Machine Learning Models

### 1. Logistic Regression
Used as an interpretable statistical baseline model for cardiovascular risk prediction.

### 2. Random Forest
Used as a machine learning ensemble model to compare predictive performance against Logistic Regression.

---

## Model Performance

| Model | Accuracy | AUC Score |
|---|---|---|
| Logistic Regression | 0.795 | 0.879 |
| Random Forest | 0.985 | 1.00 |

---

## Explainable AI (XAI)

SHAP explainability techniques were applied to improve transparency and interpretability of model predictions.

### SHAP Analysis Included
- Global feature importance analysis
- Local patient-level explanation
- Waterfall plot visualization
- SHAP summary plot

---

## Most Influential Clinical Features

The following features were identified as highly influential in heart disease prediction:

1. Chest Pain Type (`cp`)
2. Number of Major Vessels (`ca`)
3. Maximum Heart Rate (`thalach`)
4. ST Depression (`oldpeak`)
5. Thalassemia (`thal`)

These findings align with clinically relevant cardiovascular risk indicators.

---

## Key Insights

- Logistic Regression provided interpretable and statistically transparent predictions suitable for clinical understanding.
- Random Forest achieved significantly higher predictive performance.
- SHAP explainability improved transparency by identifying feature-level contributions to predictions.
- The project demonstrates the importance of balancing predictive performance with interpretability in healthcare AI systems.

---

## Discussion

The Random Forest model achieved extremely high predictive performance on the dataset. While this demonstrates strong learning capability, it may also indicate potential overfitting or dataset-specific learning patterns.

In contrast, Logistic Regression offered lower predictive performance but greater transparency and interpretability, which are important considerations in clinical decision-support environments.

This project highlights the tradeoff between predictive complexity and explainability in healthcare machine learning systems.

---

## Future Work

Potential future improvements include:
- External dataset validation
- Hyperparameter optimization
- Additional explainability methods (LIME)
- Deployment as a clinical decision-support dashboard
- Integration of fairness and bias analysis

---


## Conclusion

This project demonstrated the use of interpretable statistical and machine learning models for heart disease prediction.

The integration of Explainable AI techniques enabled both global and local interpretation of predictions, supporting the development of more trustworthy and transparent AI-assisted clinical decision systems.


