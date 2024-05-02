# credit-risk-classification

The primary goal of this challenge was to train and evaluate the regression model to predict the credibility of borrowers from a bank. Using historical dataset of lending activities from burrowers, the challenge was aimed to build a logistic regression model to classify risk loan. The analysis involved two datapoints, the “healthy loan” and the “high-risk loan”, through the regression model, and evaluating the performance, an analysis can be made on the accuracy of the model.
Results:
Accuracy: The model’s accuracy score was computed by comparing the prediction on the test set with the labels.
   precision    recall  f1-score   support

  healthy_loan       1.00      1.00      1.00     18759
high-risk_loan       0.87      0.89      0.88       625

      accuracy                           0.99     19384
     macro avg       0.94      0.94      0.94     19384
  weighted avg       0.99      0.99      0.99     19384
Precision: The precision score was calculated for both classes to determine the models ability to correctly classify each class.
Recall: The recall score was also calculated for both classes to assess how well the model captures all the instances of each class.
