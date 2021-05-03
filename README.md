# MachineLearningModule17

Overview of the loan prediction risk analysis:



  The purpose of this analysis was to predict whether or not someone would pay their credit card bills on time using a multi-factor approach. Over 100 different attributes per card holder were considered (employment data, home ownership, purpose, zip code, etc...). [Here is the link to the source data.](https://github.com/jrg12300/MachineLearningModule17/blob/main/Module_17_Challenge/LoanStats_2019Q1.csv)




Naive Oversampling:

![Oversampling](https://github.com/jrg12300/MachineLearningModule17/blob/main/Module_17_Challenge/NaiveOversampling.png)

SMOTE Oversampling:

![Oversampling](https://github.com/jrg12300/MachineLearningModule17/blob/main/Module_17_Challenge/SMOTEOversampling.png)

Undersampling:

![Undersampling](https://github.com/jrg12300/MachineLearningModule17/blob/main/Module_17_Challenge/Undersampling.png)

Combination (SMOTEENN) Sampling:

![SMOTEENN](https://github.com/jrg12300/MachineLearningModule17/blob/main/Module_17_Challenge/Combo.png)

Balanced Random Forest Classifier:

![BRFC](https://github.com/jrg12300/MachineLearningModule17/blob/main/Module_17_Challenge/BalancedRandomForestClassifier.png)

Easy Ensemble AdaBoost Classifier:

![EEABC](https://github.com/jrg12300/MachineLearningModule17/blob/main/Module_17_Challenge/Ensemble.png)


In conclusion, it is clear that the Easy Ensemble AdaBoost Classifier is the best machine learning model to use for credit card default prediction. It had the best precision, recall, & specificity.
