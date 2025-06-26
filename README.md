# Diabetes-Prediction-ML

This project focuses on predicting whether a patient is diabetic based on diagnostic health measurements. The dataset used is the PIMA Indian Diabetes Dataset, a well-known benchmark in medical machine learning problems.

---
## Dataset Details

- Source: Kaggle — https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database
- Records: 768 patients  
- Target: `Outcome` → 1 (Diabetic), 0 (Non-Diabetic)  
- Features: Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age

---

## Workflow

1. Data Cleaning:
   - Identified and replaced invalid zero values with median (e.g., 0 Glucose → medically impossible).
2. Exploratory Data Analysis:
   - Correlation heatmaps, boxplots to identify patterns and outliers.
3. Preprocessing:
   - Standardized features using `StandardScaler`
4. Model Training:
   - Logistic Regression  
   - Random Forest  
   - k-Nearest Neighbors  
5. Evaluation Metrics:
   - Accuracy, F1-Score, Confusion Matrix, ROC-AUC Curve

---

## Model Comparison

| Model               | Accuracy | F1 Score | ROC-AUC |
|--------------------|----------|----------|---------|
| Logistic Regression| 0.79     | 0.69     | 0.82    |
| Random Forest      | 0.80     | 0.71     | 0.83    |
| kNN                | 0.74     | 0.63     | 0.76    |

**Best Model:** Random Forest (Highest AUC and F1-score)

---

## Visualizations

- Confusion Matrix  
- ROC Curve Comparison

- ROC Curve ![image](https://github.com/user-attachments/assets/106bf711-f26c-4ccf-8aa4-a76b36580c6d)


Random Forest edges out other models with the highest AUC of 0.83, showing strongest classification capability.

---
## Libraries Used

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn

---

## Author

**Sahil Keswani**  
[LinkedIn](https://www.linkedin.com/in/sahil-keswani-4667422a1/)  
[GitHub](https://github.com/SK-Region)
