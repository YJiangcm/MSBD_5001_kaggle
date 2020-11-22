# MSBD_5001_kaggle
This repository contains the data and codes for MSBD_5001_kaggle_competition

The train.csv and test.csv are a little different from the original csvs downloaded from the kaggle competitions, because I crawled Hong Kong's 2017-2018 holiday data and added a column named "holiday" to the original train.csv and test.csv.

## 1. This folder contains 5 files:

---------- train.csv (containing the train dataset)  
---------- test.csv (containing the test dataset)  
---------- Xgboost_model.ipynb (containing the xgboost model for preticting the speed of the test dataset)  
---------- SVT_model.ipynb (containing the SVT model for preticting the speed of the test dataset)  

## 2. How to run these models:

### 2.1 Xgboost model
          * switch the working path to this folder
          * open the Xgboost_model.ipynb
          * run all the codes, the submission csv will be saved in the current working path

### 2.2 SVT model
          * switch the working path to this folder
          * open the SVT_model.ipynb
          * run all the codes, the submission csv will be saved in the current working path

## LICENSE
Please refer to [MIT License Copyright (c) 2020 YJiangcm](https://github.com/YJiangcm/MSBD_5001_kaggle/blob/master/LICENSE)
