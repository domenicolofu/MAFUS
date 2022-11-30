# MAFUS:
<b>A Framework to predict mortality risk in MAFLD subjects.</b>

[![Apache2.0](https://img.shields.io/badge/Apache-2.0-<COLOR>.svg)](https://shields.io/) ![version](https://img.shields.io/badge/version-1.0-brightgreen) 



The libraries used by MAFUS 1.0 are the following:

| Plugin | Version | README |
| ------ | ------ | ------ |
| Imbalanced-learn | 0.9.0 | [https://imbalanced-learn.org/] |
| Matplotlib | 3.5.1 | [https://matplotlib.org/] |
| Numpy | 1.22.3 | [https://numpy.org/] |
| Pandas | 1.4.2 | [https://pandas.pydata.org/] |
| Pickle | 4.0 | [https://docs.python.org/3/library/pickle.html] |
| Scikit-learn | 1.0.2 | [https://scikit-learn.org/stable/] |
| Seaborn | 0.11.2 | [https://seaborn.pydata.org/] |
| Scipy | 1.8.0 | [https://scipy.org/] |


| Algorithm | Hyperparameter | Values | Type | 
| ------ | ------ | ------ |------ |
| Multilayer Perceptron | seed | {1} | Integer |
|  | hidden layer sizes | {(sp randint.rvs(100, 600, 1),<br> sp randint.rvs(100, 600, 1), sp randint.rvs(100, 600, 1))} | Integer |
