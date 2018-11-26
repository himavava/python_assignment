# python_assignment

topic : Predict whether a student will pass or fail using SVM

The dataset used is "student.csv".
the python file "prediction" contain code for prediction.

Description of code:

       1. import numpy and pandas module.
       
       2. Read "student.csv" file into "data_new".
       
       3. We want to reduce the number of features, so select only wanted features specifying the 
        attribute names and store the new dataset into "new".
        
       4. Then store the predict class in variable "predictions".
       
       5. All the other attribute valuues in "feature_raw".
       
       6. From sklearn.model_selection import train_test_split function.
      
       7. Train_test_split function is called by passing features_raw, predictions, train_size=0.80, random_state=1
              and it split the entire dataset into training and testing samples.
      
       8. These are stored in X_train, X_test, y_train, y_test variables.
      
       9. Print the number of samples.
      
      10. From sklearn import svm module.
      
      11. Fit a model using "svc.fit(X_train, y_train)" by passing training values.
      
      12. Predict X_test values by calling function "svc.predict()" by passing "y_test" as argument.
      
      13. The prediction values are stored in "predictions_test" variable.
      
      14.  print "predictions_test".
       
      15. For calculating accuracy from sklearn.metrics import accuracy_score  function.
       
      16. Pass y_test and predictions_test as arguments to accuracy_score  function.
           Print accuracy.
       

       
        
