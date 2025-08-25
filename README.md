# Customer-Churn
Analysis of different classifiers with the Telco Customer Churn dataset by BlastChar

## Classifiers:
-LogisticRegression  
-SVC  
-RandomForest  
-XGB  

## Techniques used to optimize:
-SMOTE  
-Hyperparameters fine-tuning  

## Conclusion

After testing several classifiers (Logistic Regression, SVC, Random Forest, and XGBoost) Logistic Regression proved to be the most effective for this problem, achieving the best combination of precision and recall. Even after applying SMOTE and optimizing the hyperparameters, the model achieves a moderate accuracy of 63%, reflecting that the imbalance of class 1 continues to limit overall performance. Nevertheless, Logistic Regression provides a solid starting point and a clear benchmark for comparing future improvements, whether through additional balancing techniques or more complex models.
