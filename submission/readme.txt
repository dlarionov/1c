1c features.ipynb produces file 'feature_matrix.pickle' which is ~2Gb size. 

This file is used by several classifiers:
1c catboost.ipynb
1c xgb.ipynb
1c random_forest.ipynb

Each classifier gives predictions for the test and validation sets. All predictions store in the files '*_train.pickle' and '*_test.pickle', which is used by 1c ensemble.ipynb to make final predictions.

xgb_model.pickle - best classifier