Heart Disease Prediction  (Classification)
===========================================
                          -Vaibhav Haswani

**Note:** The notebook can take a long time to run totally depending on your machine's computation power as algorithms like `RandomizedSearchCV` and `GridSearchCV` are used in the Project.

## Project Description
Heart Disease Prediction (Classification based problem) data is taken from the [Cleveland database](https://archive.ics.uci.edu/ml/datasets/heart+Disease) from UCI Machine Learning Repository.
Evaluation is done using different Algorithms(LogisticRegression,Knearest neighbors,Random Forests)
Final evaluation is done using `Logistic Regression`


## REPORT (of final evaluation)

* Accuracy:91%
* AUC:93%
* RECALL,PRECISION,F1: 92% ,92% ,92%
* CROSS VALIDATED-
                * Accuracy:84.7%
                * RECALL,PRECISION,F1: 82% ,92.7% ,87%


## Project Environment

"Make sure your working environment is same as in the env.yml if not use the following command to create custom conda environment from env.yml in"-
`conda env create --file env.yml `