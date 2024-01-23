
**CREDIT CARD FRAUD DETECTION**

-Build a model to detect fraudulent credit card transactions. Use a dataset
containing information about credit card transactions, and experiment with
algorithms like Logistic Regression and Random Forests to classify
transactions as fraudulent or legitimate.

**Dataset Used** :  https://www.kaggle.com/datasets/kartik2112/fraud-detection

**Conclusion** : **Key Takeaways**

-Highest Training & Validity Accuracy: Random Forest at 100%.
-Handling Missing Values: Imputed missing values using the mode.
-Handling Target Variable Imbalance: Used undersampling using RandomUnderSampler to address the imbalance.
-Hyperparameter Tuning: Employed GridSearchCV for optimizing hyperparameters.
-Cross-validation: Utilized StratifiedKFold cross-validation for robust model evaluation.
-Save Model : Saved model using Joblib & applied that model on our test dataset to classify transactions as fraudulent or legitimate.
