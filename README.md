# credit-risk-classification

The primary goal of this challenge was to train and evaluate the regression model to predict the credibility of borrowers from a bank. The challenge was to build a logistic regression model to classify risk loan using a historical dataset of lending activities from burrowers. The analysis involved two datapoints, the “healthy loan” and the “high-risk loan”, through the regression model, and evaluating the performance, an analysis can be made on the accuracy of the model.
Results:

**Accuracy**: The model’s accuracy score was computed by comparing the prediction on the test set with the labels.

Healthy Loans:

  	Precision: 1.00
  	Recall: 1.00
  	F1-score: 1.00
  	Support: 18,759 instances
  
High-Risk Loans:

	  *Precision: 0.87
	  *Recall: 0.89
	  *F1-score: 0.88
	  *Support: 625 instances
   
Overall Accuracy: The model achieved an accuracy of 99% across all instances in the test set.
Macro Average:

	  Precision: 0.94
	  Recall: 0.94
	  F1-score: 0.94
Weighted Average:

	  Precision: 0.99
	  Recall: 0.99
	  F1-score: 0.99

  
**Precision**: The precision score was calculated for both classes to determine the models ability to correctly classify each class.


**Recall**: The recall score was also calculated for both classes to assess how well the model captures all the instances of each class.

The model performed exceptionally well in classifying both healthy and high-risk loans. The high precision and recall scores, particularly for healthy loans, indicate that the model can accurately identify these cases. The close alignment of macro and weighted averages suggests a balanced performance across both classes.

**Conclusion**
The model's high accuracy and strong performance metrics make it a promising tool for assessing loan risk. Further testing and tuning may help optimize its application in a real-world setting.
