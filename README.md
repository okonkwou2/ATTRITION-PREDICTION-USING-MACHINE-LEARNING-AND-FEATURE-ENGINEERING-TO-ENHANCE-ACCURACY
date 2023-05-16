# 7151CEM-ATTRITION-PREDICTION-PYTHON
ATTRITION PREDICTION USING MACHINE LEARNING AND FEATURE ENGINEERING TO ENHANCE ACCURACY
Employee attrition is the voluntary or involuntary termination of an employee in an organization, and it is a significant concern for most organization with a functioning HR department as it affects not just their efficiency or work sustainability but also their long-term development tactics. This research work focuses on discussing the combination of various systematic machine learning techniques and statistical data analysis to enhance the predictive accuracy of employee attrition.
The steps taken to achieve this are as follows: data acquisition, exploratory data analysis, data cleaning, feature engineering which includes skewed feature transformation using the box-cox power transformation, determining predictive power of categorical variables using chi-square method for feature selection before encoding all categorical features, applied synthetic minority over-sampling technique (SMOTE) to tackle data imbalance before applying standard scaling and creating a dataset with cleaned features, dataset with reduced feature and dataset with all features. The data split was train-validation-test at 60%-20%-20% respectively. Then I ran 5-fold cross validation on each of the feature sets and selected the best models using the Random Forest classifier, afterwards I evaluated the models on the validation set and picked the best one. Finally, I evaluated that best model on the test set to gauge the model’s ability to generalize to unseen data and to confirm its consistency. The evaluation was based on the model’s accuracy, precision, recall, f-score, roc-auc and latency or computational speed.
The dataset with clean features and SMOTE applied on the train set gave a maximum accuracy of 91% with max depth of 16 and 32 estimator while the minimum accuracy was 79% with max depth of 2 and 16 estimators this happens to be the best results compared to the other 5 various feature sets. At the validation stage, the accuracy was 85.7%, precision was 60.9%, recall was 30%, f1-score was 0.40, roc-auc was 0.631 and latency was 49.3ms. Finally, at the test stage we had an accuracy of 87.8%, precision of 65.2%, recall of 35%, f1-score of 0.455, roc-auc score became 0.658 and latency of 49.5ms. These results show the influence of the combined techniques in enhancing the accuracy of the attrition class prediction model. Additional analysis was carried out to help the HR department identify the key factors that influence attrition which could help them in minimizing it and enhance retention on the other hand.
