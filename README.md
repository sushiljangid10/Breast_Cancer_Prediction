Breast_Cancer_Prediction

Project Description

This project involves predicting breast cancer diagnoses using machine learning techniques. The dataset provided includes various features related to breast cancer, and the objective is to classify tumors as malignant or benign.


Key Steps and Findings

Data Analysis and Preprocessing


Exploration: Analyzed feature correlations with the diagnosis column.

Feature Selection: Identified and selected columns with high correlations for model training.

Outlier Detection: Used Local Outlier Factor (LOF) to identify and remove outliers to improve model performance.

Data Scaling: Applied feature scaling using StandardScaler to standardize features for better model performance.

Model Training and Evaluation


Models Used: Logistic Regression, K-Nearest Neighbors, Support Vector Machine (SVC), Decision Tree, Random Forest, Gradient Boosting, AdaBoost, and XGBoost.

Accuracy Assessment: Evaluated each model's accuracy and compared their performances. The highest accuracy achieved was 98.25% with Logistic Regression.

Model Performance Visualization: Plotted accuracies of different models to visualize their performance.

Hyperparameter Tuning


Logistic Regression Optimization: Conducted experiments to determine the impact of different random states on model accuracy, aiming for improvements in prediction performance.

Results

Best Performing Model: Logistic Regression with 98.25% accuracy.

Correlation Insights: Identified columns with high correlation to the diagnosis column, aiding in feature selection.

Outlier Impact: Removed outliers to refine model training and improve overall prediction accuracy.


