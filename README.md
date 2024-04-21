## Introduction:

This report summarizes the development of models to predict numbers drawn by students in a writing test using a dataset of pixel intensity values of the letters. The goal is to identify students who may need to work on their motor skills at a young age.

## Data Cleaning:

The dataset comprises 42,000 observations with no missing values or special characters. All variables are integers, with 'Label' as the target variable.

**K Nearest Neighbors (KNN) Model:**

Two KNN models were built, with 'k' values of 205 and 103, achieving accuracies of 61.12% and 63.38% respectively. Both models performed best in predicting label '6'.

**Random Forest Model:**

Two Random Forest models were constructed with 100 and 200 decision trees, yielding accuracies of 60% and 59.95% respectively. Label '6' was consistently the best-predicted class.

**Neural Network Model:**

Two neural network models using different activation functions achieved accuracies of 66.79% and 66.45% respectively. Label '1' was the best-predicted class in both models.

**Model Comparison:**

The neural network consistently outperformed KNN and Random Forest models in accuracy, precision, and F1 score. Label '6' and '1' were best predicted across all models.

**Conclusion:**

The neural network model is recommended for predicting students' handwriting, particularly labels '1' and '6'. This data-driven approach enables targeted interventions to enhance students' motor skills from an early age.

**Future Work:**

Further improvements are needed to predict labels '2', '3', '4', '5', '7', '8', and '9' more accurately.







