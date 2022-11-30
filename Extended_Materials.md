# MAFUS:
<b>A Framework to predict mortality risk in MAFLD subjects.</b>

[![Apache2.0](https://img.shields.io/badge/Apache-2.0-<COLOR>.svg)](https://shields.io/) ![version](https://img.shields.io/badge/version-1.0-brightgreen) 


The list below, reports explored hyperparameter values, list, and type for reproducibility:


| Algorithm | Hyperparameter | Values | Type | 
| ------ | ------ | ------ |------ |
| <b>Multilayer Perceptron</b> | seed | {1} | Integer |
|  | hidden layer sizes | {(sp randint.rvs(100, 600, 1),<br> sp randint.rvs(100, 600, 1), <br> sp randint.rvs(100, 600, 1))} | Integer |
|  | activation | {tanh, relu, lbfgs} | String |
|  | solver | {sgd, adam, lbfgs} | String |
|  | alpha | {0.0001, 0.001, 0.01, 0.1, 0.9} | Float |
|  | learning_rate | {constant, adaptive} | String |
| <b>Random Forest</b> | seed | {1} | Integer |
|  | n_estimators | {100, 200, 300, 400, 500} | String |
|  | max_features | {auto, sqrt, log2} | String |
|  | max_depth | {80, 90, 100, 110, 120, 130, 140, 150, None} | String |
|  | criterion | {gini, entropy} | String |
|  | class_weight | {balanced} | String |
| <b>Support Vector Machine</b> | seed | {1} | Integer |
|  | class_weight | {balanced} | String |
|  | kernel | {rbf, linear} | String |
|  | gamma | {1, 0.1, 0.001, 0.0001} | Float |
| <b>eXtreme Gradient Boosting</b> | seed | {1} | Integer |
|  | gamma | {1, 0.1, 0.01, 0.001, 0.0001} | Float |
|  | learning_rate | {0.0001, 0.001, 0.01, 0.1, 1} | Float |
|  | max_depth | {3, 21, 3} | Integer |
|  | colsample_bytree | {1/10.0 for i in range(3,10)}  | Float |
|  | reg_alpha | {1e-5, 1e-2, 0.1, 1, 10, 100}  | Float |
| <b>Light Gradient Boosting</b> | seed | {1} | Integer |
|  | learning_rate | {0.1, 0.005} | Float |
|  | num_leaves | {3, 10, 31, 50, 100, 200} | Integer |
|  | reg_alpha | {None, 0.01, 0.05, 0.1} | Float |
|  | colsample_bytree | {0.6, 0.8, 1} | Float |
|  | max_depth | {-1, 3, 5, 8, 10} | Integer |
|  | reg_lambda | {None, 0.01, 0.02, 0.03} | Float |
|  | n_estimators | {50, 100, 300} | Integer |








