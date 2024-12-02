# Fraudulent-Transaction-Detection

This project focuses on designing a robust machine learning pipeline to detect fraudulent transactions efficiently. Using advanced data preprocessing techniques, feature optimization, and ensemble learning methods, the system achieves high performance in classifying transactions as fraudulent or non-fraudulent.

## Features
- **Imbalanced Dataset Handling**: Addressed class imbalance using SMOTE (Synthetic Minority Oversampling Technique).
- **Model Training and Evaluation**: Utilized Stratified K-Fold Cross-Validation and hyperparameter tuning with GridSearchCV.
- **Algorithms Used**:
  - Random Forest (achieved the highest AUC score: 0.9295)
  - XGBoost
  - Logistic Regression
 
## Results
- **Random Forest**:
  - AUC: 0.9295 (best-performing model)
  - Hyperparameters optimized using GridSearchCV.
- **XGBoost**:
  - AUC: 0.8976
- **Logistic Regression**:
  - AUC: 0.7348
