Model được xây dựng Bằng Bagging Hold-out 2/3 train 1/3 test
Tham số:
estimator=DecisionTreeClassifier(max_depth=50, criterion='entropy',
min_samples_split=4, min_samples_leaf=4, class_weight='balanced'),
n_estimators=200, #bootstrap_features=True,
             random_state=42)

Accuracy:  0.898500860162202
Precision:  0.9007913479053098
Recall:  0.898500860162202
F1_Score:  0.8995498689760961

