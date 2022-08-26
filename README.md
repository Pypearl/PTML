# PTML [![Profile][title-img]][profile]

[title-img]:https://img.shields.io/badge/-SCIA--PRIME-red
[profile]:https://github.com/bictole

## Objective

The goal of this project is to apply and demonstrate the use of different **machine learning** methods to real datasets.

## Dataset

We had to choose two **datasets** within the following constraints :
* several hundreds of lines
* at least 6 attributes (columns), the first being a unique id, separated by commas
* we may use some categorical (non quantitative) features.
* some fields should be correlated

Obvously, we had to tweak the datasets in order to artificially make it possible to apply **analysis** and **visualization** techniques on them.


## Analysis

The analysis is made with python on the `MLSECU_SG_AL_VS.ipynb` notebook. We are going through the whole analysis process, with the **dataset exploration**, the **cleaning**, the **feature engineering**, **statistical analysis**, **visualization** and finally the **machine learning** part.

## Results

To compare our **supervised** classification model algorithms, we compared their f1_score to see which fit the data. We observed that the tree-based models, in particular the **RandomForest**, are those that obtains the best results.

<img src="https://github.com/Bictole/MLSECU/blob/master/bench.png" alt="Benchmarks_Results">

We also tested **XGBoost**, its results are excellent, with more than 94% of F1_score obtained for a test dataset with 1000 anomalies out of 10 000 network exchanges.

## Authors

alexandre.lemonnier\
alexandre.poignant\
sarah.gutierez\
victor.simonin