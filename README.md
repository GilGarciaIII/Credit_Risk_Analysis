# Credit_Risk_Analysis

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. 

### Use Resampling Models to Predict Credit Risk: 
Used three machine learning models by using resampling to determine which is better at predicting credit risk. SMOTE algorithms oversampling RandomOverSampler resampled the dataset, viewed the count of the target classes, trained a logistic regression classifier, calculated the balanced accuracy score, generated a confusion matrix, and generate a classification report.

-Balanced accuracy score: 65%
-high risk: 0.01%
-low risk: 1%
-recall high risk: 63%
-recall low risk: 67%

<img width="977" alt="Screen Shot 2022-03-08 at 12 03 18 AM" src="https://user-images.githubusercontent.com/88943257/172768391-71cf030f-90d1-44c9-b857-ed0d57956680.png">

-Balanced accuracy score: 79%
-Precision high risk: 0.4%
-Precision low risk: 1%
-recall high risk: 67%
-recall low risk: 91%

<img width="1044" alt="Screen Shot 2022-03-08 at 12 12 46 AM" src="https://user-images.githubusercontent.com/88943257/172768576-539db721-348c-40c4-a32c-c94c0e8b6f47.png">


-Balanced accuracy score: 61%
-Precision high risk: 0.1%
-Precision low risk: 1%
-recall high risk: 69%
-recall low risk: 55%

<img width="1020" alt="Screen Shot 2022-03-08 at 12 28 01 AM" src="https://user-images.githubusercontent.com/88943257/172768646-bcf0e8f7-ac79-4cb8-9727-095521eae78b.png">

  
