### credit-card-fraud-transaction-MLFLOW
Context
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

Content
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
https://www.kaggle.com/mlg-ulb/creditcardfraud

### How you can use MLflow end-to-end.


###  Comparing the Models
Use the MLflow UI to compare the models that you have produced. In the same current working directory as the one that contains the mlruns run:
mlflow ui

and view it at http://localhost:5000.
On this page, you can see a list of experiment runs with metrics you can use to compare the models.
![alt text](https://github.com/shosseini811/credit-card-fraud-transaction-MLFLOW/blob/e64dcc2869866fa447387d5181081d2e13522e82/multiple_runs.png)





