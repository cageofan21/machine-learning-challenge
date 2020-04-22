# machine-learning-challenge

GridSearch was used in the model 1 (SVM) and model 2 (LogisticRegression). In model 3, I used DecisionTree and RandomForest. In both model 1 and model 2, it can predict the "False Positive" in the ["koi_disposition"] column at 98% accuracy. After doing the Hyperparameter Tuning, the testing score in the SVM model is slightly higher than the one in Model 2 (LogisticRegression). 

The testing score in the Decision Tree model is lower than in any other model. This is because when decision tree becomes more complex with lots of values, it may not generalize well.  The testing score value when doing RandomForest is higher than the value when using decision tree. However, with RandomForest, it is estimating with 200 nodes, meaning we are breaking chuck of data to 200 nodes. Each one of the nodes is a weak classifier but when combined, they are strong. 
