# python_assignment

topic : Predict whether a student will pass or fail using SVM

The dataset used is "student.csv".
the python file "prediction" contain code for prediction.
Description of dataset:

            age :  student's age (numeric: from 15 to 22)
            
            Medu : mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 :5th to 9th grade, 
                   3 : secondary education or 4 :higher education)
                   
            Fedu : father's education (numeric: 0 - none, 1 - primary education (4th grade), 
                   2 : 5th to 9th grade, 3 â€“ secondary education or 4 : higher education) 

            traveltime : home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 
                         3 - 30 min. to 1 hour, or 4 - >1 hour) 

            studytime : weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours) 

            failures  : number of past class failures (numeric: n if 1<=n<3, else 4) 

            famrel : quality of family relationships (numeric: from 1 - very bad to 5 - excellent) 

            freetime : free time after school (numeric: from 1 - very low to 5 - very high) 

            goout : going out with friends (numeric: from 1 - very low to 5 - very high) 

            Dalc :  workday alcohol consumption (numeric: from 1 - very low to 5 - very high) 

            Walc : weekend alcohol consumption (numeric: from 1 - very low to 5 - very high) 

            health : current health status (numeric: from 1 - very bad to 5 - very good) 

            absences : number of school absences (numeric: from 0 to 93) 

           passed : pass or fail (1 for pass and 0 for fail )

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
       

       
        
