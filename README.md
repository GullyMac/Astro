# Astro Type Classification

This project is an entry for the 2nd Monthly Data Analysis Competition organized by DACON.

DACON main : https://newfront.dacon.io/

Competition Info. : https://dacon.io/competitions/official/235573/overview/

Report : https://github.com/GullyMac/Astro/blob/master/astro.ipynb

20.04.23 last edit

---

## 0. Environment

* Language : Python
* Editor : Google Colaboratory (Jupyter Notebook)

   ! Performance can change depending on the hardware allocated by Colab.
   
* CPU : Intel® Xeon®
* RAM : about 25GB
* Disk : about 68GB
* GPU : Tesla P100

   ! When using GPU, there are a little of differences in result.
   
---

## 1. Introduction

#### Background:

Sloan Digital Sky Survey (SDSS) collects astronomical data about the universe.

The data collected here have been used in about 6,000 papers, and have contributed significantly to astronomy to more than 250,000 citations.

By analyzing this data, uncovered rules (of classifying stars) can be revealed.

#### Organizer: DACON

#### Metric: LogLoss

---

## 2. Data Set

#### Data Sets are provided by DACON

#### Response Variable

* type

#### Explanatory Variable

* psfMag, fiberMag, petroMag, modelMag, fiberID

---

## 3. Library

#### Environment Setting

* google.colab.drive : mount at google drive
* warnings : ignore warning message
* os : directory setting

#### Data Manipulation

* pandas : data manipulation
* numpy : matrix operation
* random : random number generation
* time : time measurement

#### Visualization

* matplotlib.pyplot : graph drawing

#### Modeling

* sklearn.model_selection.train_test_split : seperate train and validation data set
* sklearn.model_selection.KFold : k-fold cross validation
* sklearn.metrics : residual measurement
* bayes_opt : Bayesian optimization
* functools.partial : freeze a function’s arguments
* catboost : CatBoost modeling
* lightgbm : lightGBM modeling

