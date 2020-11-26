# Machine-Learning
Machine Learning Algorithms Performed on various datasets and a thorough comparison of all the models with each other.

## 📍 Regression on Toyota Corolla Dataset.
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
  
### ✳ Ensemble and Dimension Reduction Machine Learning Regression Models.
1) Using the same dataset, in part 2, we worked on the following Ensemble models and further more performed the PCA(Principal Componenet Analysis) to reduce the dimension    and re working with the above discussed Machine Learning Models.
2) Ensemble Modles Used: Bagging, Pasting, Adaboost on KNN Regressor and Decision Tree Regressor and Gradient Boosting.
3) Amongst these the Bagging Decision Tree and the Pasting Decision Tree provided the best outcome with higher test scores and lesser difference in train and test scores.
4) The PCA reduced the dataset from 86 dimensions to 37. The result of running PCA dataset on each of this models above, including Deep Learning( Tensor Flow & Keras), and showed a reduction in train and test score thus reducing the overall precision and accuracy of the model making it not fit for this dataset.


## 📍 Classification on Bank Loan Dataset.
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

### ✳ Ensemble and Dimension Reduction Machine Learning Classification Models.
1) Using the same dataset, in part 2, we worked on the following Ensemble models and further more performed the PCA(Principal Componenet Analysis) to reduce the dimension    and re working with the above discussed Machine Learning Models.
2) Ensemble Modles Used: Voter Classifier: Hard & Soft, Bagging, Pasting, Adaboost on Logistic Regression and Decision Tree Regressor and Gradient Boosting.
3) Amongst these the Bagging Decision Tree and the Pasting Decision Tree provided the best outcome with higher test scores and lesser difference in train and test scores.
4) The PCA reduced the dataset from 75 dimensions to 48. The result of running PCA dataset on each of this models above, including Deep Learning( Tensor Flow & Keras), showed very less reduction in train and test accuracy score thus making it perfect fit as it would reduce the dimensionality and provide accurate results.


