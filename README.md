#TASK-03:
Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning Repository.

Data Cleaning
Handled missing values by filling with median values.
Detected and removed outliers using the Z-score method.
Checked and handled multi-collinearity by removing highly correlated features.

Model Training
Used a Decision Tree Classifier to predict fraudulent transactions.
Split the data into training (70%) and testing (30%) sets.
Evaluated the model using accuracy, confusion matrix, and classification report.

Results
Accuracy: 87%

Confusion Matrix:
[[11057   909]
 [  862   736]]
 
Classification Report:
              precision    recall  f1-score   support

     False       0.93      0.92      0.93     11966
      True       0.45      0.46      0.45      1598

  accuracy                           0.87     13564
 macro avg       0.69      0.69      0.69     13564
 
weighted avg 0.87 0.87 0.87 13564
