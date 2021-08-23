# CASA0012-Dissertation

This repo is to store my dissertation file and present my disseration book

```
- bookdown #the path of dissertation book
- jupyterlab #the path of research progress log
- code #the path of the reproducible analysis and map making
```
## Reproducible Analysis Process

|Name|Link|
|:--:|:--:|
|Multiple regression analysis - attendance time|	https://yolandayingying.github.io/CASA0012-Dissertation/html/linear_regression.html|
|fire Hierarchical clustering|https://yolandayingying.github.io/CASA0012-Dissertation/html/Fire_HCluster.html|

## Reference

0. We have not done a lot to interpret the models. If you have time and energy, here is a handy book on interpretation of statistics and machine learning models. For linear regression, please read this [this chapter](https://christophm.github.io/interpretable-ml-book/limo.html). For decision trees, have a look at [this chapter](https://christophm.github.io/interpretable-ml-book/tree.html). If you want to interpret a random forest, you can try the **permutation feature importance** method, which is introduced in [this chapter](https://christophm.github.io/interpretable-ml-book/feature-importance.html).
1. We committed a methodological sin in reusing the same dataset for model fitting and validation (calculting the goodness-of-fit). There are ways around this problem, either by using another dataset, or by splitting the dataset into parts for *cross-validation*. Look at the documentation on cross-validation [here](ttp://scikit-learn.org/stable/modules/cross_validation.html)and then implement a simple technique to avoid this problem.
2. There are lots of nice datasets for analysis on [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets.html) and [Kaggle](https://www.kaggle.com/datasets). Take a look, and if any of them take your fancy try create a regression model. Which data features are important? Which are not? 











