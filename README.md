# Learning Machine Learning
This Repository contains Machine Learning concepts and recipes.
## Basic Steps to solve Machine Learning Problems:
ML Basic Steps:
- Data Pre-processing/Data Engineering:
- Read Data
- Identify the info
- Describe the data
- Handling missing/null values
- Checking categorical values and check the need of one-hot-encoding
- Visualise data with histogram/scatter plot etc. to see any relation or pattern
- Identify the positive/negative co-relation with the Target/Label values
- Heat-map to show the co-relation between the columns
- Feature Engineering and Model Evaluation:
- Standard scaler can be used to scale the data if required
- Splitting training data with train_test_split/Cross_val_score
- basic check on different models with default hyper parameters.
- Using GridSearchCV/RandamizedSearchCV to identify the model selection and its best parameter
### Machine Learning Model Prediction:
- Once the model and best parameter is decided, accuracy is being checked
- For classification problems, Confusion Metrics is also generated to find the TN, TP, FN and FP
- Depending on the scenario, further tuning can be done
- Predict the values.
#### Notes: train-test-split can be used before using cross_val_score, as it gives one set of testing data to final check on our model prediction before using unknown data for prediction.
### Jupyter Notebook: Kaggle Tabular Playground Series Jan2021.ipynb
- Contains example of Regression Algorithms and its hyper-params tuning using Grid Search CV
- Data Set is from Kaggle Competition: Kaggle Tabular Playground Series Jan2021
- Current LeaderBoard score is in top 42% need to refine :)


