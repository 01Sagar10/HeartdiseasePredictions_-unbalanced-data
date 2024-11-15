[ Summarising the best Model out of different models in the project ] 

[ Feature engineering on "non_null" data- with and without oversampling
1a.Data = 0s removed from Physical and Menthal health features
Run different models after finding best paramters in RandomSearchCV
Returning Classification report, confusion matrix
Calculating AUC scores
Caculating best threshold for classification by (TPR - FPR)
Returning Classification reports after predicting on Best Threshold ]

  [         precision    recall  f1-score   support
       0       0.97      0.67      0.80     45968
       1       0.21      0.82      0.33      4768

accuracy                           0.69     50736
macro avg       0.59      0.75     0.56     50736
weighted avg    0.90      0.69     0.75     50736 ]

[ Confusion Matrix 
[30927 15041]
[ 838 3930] ]
[ AUC Score (GB): 0.819 ]
