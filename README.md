# Credit_risk_challenge
The deliverables for this Challenge are as follows:

Deliverable 1: Use Resampling Models to Predict Credit Risk
Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk
Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
Deliverable 4: A Written Report on the Credit Risk Analysis (README.md)

Your credit_risk_resampling.ipynb file; https://github.com/Jrobinson3/Credit_risk_challenge/blob/main/credit_risk_resampling-updated.ipynb
.
Your credit_risk_ensemble.ipynb file; https://github.com/Jrobinson3/Credit_risk_challenge/blob/main/credit_risk_ensemble.ipynb

## Written Analysis
1. Overview of the analysis: Explain the purpose of this analysis.
The purpose of this analysis is to predict credit risk through various machine learning models to see which model has a best performance.     
2. Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

 ## Random oversampler summary
![image]https://github.com/Jrobinson3/Credit_risk_challenge/blob/main/Oversampling%20summary.png
1) the balanced accuracy score is 57.40% and it is considered low.
2) the precision for prediction of fraudulent transaction is 1% and very low, however sensitivity (recall) for prediction of fraudulent activity is 45% and it is medium.   

 ## Undersampling summary
![image]https://github.com/Jrobinson3/Credit_risk_challenge/blob/main/undersample.png
1) the balanced accuracy score is 53.32% and it is considered low.
2) the precision for prediction of fraudulent transaction is 1% and very low, however sensitivity (recall) for prediction of fraudulent activity is 53% and it is medium.   

 ## SMOTE summary
![image]https://github.com/Jrobinson3/Credit_risk_challenge/blob/main/SMOTE%20summary.png
1) the balanced accuracy score is 64.62% and it is considered low.
2)the precision for prediction of fraudulent transaction is 1% and very low, however sensitivity (recall) for prediction of fraudulent activity is 56% and it is medium.  

 ## Combination summary
![image]https://github.com/Jrobinson3/Credit_risk_challenge/blob/main/combination.png
1) the balanced accuracy score is 65.44% and it is considered medium.
2) the precision for prediction of fraudulent transaction is 1% and very low, however sensitivity (recall) for prediction of fraudulent activity is 73% and it is high.   

 ## Forest Classifier summary
![image]https://github.com/Jrobinson3/Credit_risk_challenge/blob/main/randomforest.png
1) the balanced accuracy score is 77.26% and it is considered medium-high.
2) the precision for prediction of fraudulent transaction is 3% and still low, however sensitivity (recall) for prediction of fraudulent activity is 66% and it is medium-high.

# Random oversampler summary
https://github.com/Jrobinson3/Credit_risk_challenge/blob/main/Oversampling%20summary.png
1) the balanced accuracy score is 57.40% and it is considered low.
2) the precision for prediction of fraudulent transaction is 1% and very low, however sensitivity (recall) for prediction of fraudulent activity is 45% and it is medium.   
   
 ## AdaClassifier summary
https://github.com/Jrobinson3/Credit_risk_challenge/blob/main/adaclassifier.png
1) the balanced accuracy score is 65.85% and it is considered medium.
2) the precision for prediction of fraudulent transaction is 3% and still low, however sensitivity (recall) for prediction of non-fraudulent activity is 66% and it is medium-high. 
  
4. Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
All of machine learning models performed above are not good to use or recommend since accuracy is not high enough nor sensitivity score is not low enough to be safe.  I would do additional procedure or seek another machine learning model to recommend.  

