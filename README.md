# Machine-Learning
Machine Learning Algorithms Performed on various datasets and a thorough comparison of all the datasets with each other.

## Regression on Toyota Corolla Dataset.
Steps:
1) Using the Kaggle Toyota Corolla Dataset we imputed 5% NaN values to replicate real life datasets.
2) We processed the data by getting rid of the NaN values using mean, median and mode imputation.
3) Once the dataset was ready, It was split into feature and target datasets and again into train and test datasets.
4) Min-Max scaler was used for this dataset because of its skewed nature.
5) The following regression techniques were used to determine which technique works for the dataset the best:
  a) K Neighbors Regressor
  b) Linear Regression using Normal Equation
  c) Ridge Regression
  d) LASSO Regression
  e) Polynomial Regression
  f) Linear SVM Regression
  g) SVM with Linear Kernel
  h) SVM with Poly Kernel
  i) SVM with RBF Kernel
  j) Decision Tree Regressor
  k) SGD Regressor

Conclusion: The SGD Regressor best fitted the model and after the conclusion we demonstrated how the predicted values are close to the actual values.

## Classification on Bank Loan Dataset.
Steps:
1) Using the Kaggle Bank Loan Dataset we imputed 5% NaN values to replicate real life datasets.
2) We processed the data by getting rid of the NaN values using mean, median and mode imputation.
3) Once the dataset was ready, It was split into feature and target datasets and again into train and test datasets.
4) Min-Max scaler was used for this dataset because of its skewed nature.
5) The following regression techniques were used to determine which technique works for the dataset the best:
  a) KNN Classifier
  b) Logistic Regression
  c) Linear Support Machine Vector
  d) Kernalized SVM using RBF Kernel
  e) Kernelized SVM using POLY kernel
  f) Kernelized SVM using LINEAR kernel
  g) Decision Tree Classifier
6) We used different evaluation functions to analyze the models based on: Cross Validation Score, Train and Test Score, Confusion Matrix - Accuracy, Precision and Recall
Precision Recall Curve, ROC Curve, F1 Score and ROC_AUC Score 
Conclusion: The Linear Support Vector Model best fitted the dataset based on the ROC_AUC Score, the F1 Score and the difference between train and test score. After the conclusion we demonstrated how the predicted values are close to the actual values.




