# Model Testing


This project writes a class or function to train, test, and store results for Fannie Mae Single-Family Loan Performance Data
(Acquisition and Performance, 2010 Q1) for the following machine learning models:
- Decision Tree
- Random Forest
- Support Vector Machine
- TensorFlow Network

This code:
 - accepts four inputs `X_train`, `y_train`, `X_test`, and `y_test`, 
 - trains the model on `X_train` and `y_train`, 
 - scores the results using `X_test` and `y_test`
 - Prints out the confusion matrix for each of the models, and 
 - Returns the result of the scoring as Python dictionary
