# credit-risk-classification

This Challenge uses various techniques to train and evaluate a model based on loan risk. A dataset of historical lending activity from a peer-to-peer lending services company is used to build a model that can identify the creditworthiness of borrowers. 
The following steps were carried out to produce the analysis:

* The data was split in to training and testing sets
* A logistic regression model was created using the original data
* A logistic regression model was created using resampled training data

## Results

* Machine Learning Model 1 (logistic regression model with original data):
    * Precision(0/1): 1.0/0.85
    * Recall(0/1): 0.99/0.91
    * F1-Score(0/1): 1.0/0.88
 
 * Machine Learning Model 2 (logistic regression model with resampled data):
    * Precision(0/1): 1.0/0.84
    * Recall(0/1): 0.99/0.99
    * F1-Score(0/1): 1.0/0.91
   
## Summary 

The logistic regression modle using the original data predicted the healthy loans(0) withe a precision of 1 and high-risk loans(1) with a lower precision of 0.85. The f1-score for healthy loans is 1 demostrating that the model is performing very well, hoeever the f1-score is 0.88 for the highe risk loan which means it needs further improvement. The models performance is seen to improve when using resampled data. The f1-score for the healthy loan is still 1 using the oversampled data, however it has imporved from 0.88 to 0.91 for the high risk loans using the oversampled data indicating that the logistic regression model is performing better with the over sampled data. Therefore usin the Machine learning Model 2 is preferred as predicting the high risk loans with greater accuracy is more desireable. 







