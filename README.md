
# Predicting Diabetes Type Using Gradient Boosting Classifier

## Objective 
This project successfully predicts the type of diabetes (e.g., Type 1 Diabetes, Type 2 Diabetes, LADA, Neonatal Diabetes) using medical and health attributes such as Genetic Markers, Autoantibodies, Insulin Levels, BMI, Blood Pressure, and more.

## Preprocessing 
- **Missing Data Handling**: Missing data was addressed using imputation techniques to ensure no information was lost and the dataset remained consistent.
- **Categorical Encoding**: Categorical variables were encoded using a combination of one-hot encoding and label encoding, depending on the feature requirements.

## Model Training and Evaluation 
- **Model Training**: The Gradient Boosting Classifier was trained using Grid Search to optimize hyperparameters. This ensured the best configuration for performance on the dataset.
- **Evaluation Metrics**: The model was evaluated based on multiple metrics, including:    
Accuracy: 0.91
Precision: 0.92
Recall: 0.91
F1-score: 0.91

These features may seem underwhelming unless you consider the lack of data surrounding Secondary Diabetes. Many features such as Type 2 diabetes have better scoring

## Feature Importance 
- **Feature Importance Plot**: A feature importance analysis was conducted to determine the most significant attributes influencing the model's predictions. The plot and its implications demonstrate which features had the greatest impact on predicting the diabetes type.

---
