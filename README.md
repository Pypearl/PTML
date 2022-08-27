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


## Supervised learning

In a first part, we had to work on a dataset and perform **supervised learning** on it. We decided to work on mobile price **classification**, and try to find some relation between features of a mobile phone (RAM, number of cores, internal memory...) and its selling price. 

We found a dataset that instead of giving the actual price of each phone give a price range indicating how high the price is.

We could perform different analysis ont this dataset and try to visualize our data.

<img src="https://github.com/Pypearl/PTML/blob/main/readme_images/supervised_vis.png" alt="Supervised_Visualization">

We decided to test several algorithms with the **sklearn** and **xgboost** library.
First, we split our data to obtain a train dataset and a test dataset, then we iterate on the **classifier** to fit them and test them. The scoring is here a `R2 score`, which is evaluated by **cross validation**.

The results are the following :

<img src="https://github.com/Pypearl/PTML/blob/main/readme_images/supervised_res.png" alt="Supervised_Visualization">


## Authors

alexandre.lemonnier\
alexandre.poignant\
sarah.gutierez\
victor.simonin