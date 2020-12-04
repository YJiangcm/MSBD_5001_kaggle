# MSBD_5001_kaggle
This repository contains the data and codes for MSBD_5001_kaggle_competition. All the codes were written based on **python programming language**.

The train.csv and test.csv are downloaded from the kaggle competitions, and "weather.csv" is crawled from  http://www.worldweatheronline.com/.

## 1. This folder contains 5 files:

---------- data \
-------------------- train.csv (containing the train dataset) \
-------------------- test.csv (containing the test dataset) \
-------------------- weather.csv (containing the weather data) \
---------- Xgboost_model.ipynb (containing the xgboost model for preticting the speed of the test dataset)  
---------- SVT_model.ipynb (containing the SVT model for preticting the speed of the test dataset)  
---------- xgb_speed_prediction.csv (prediction result by using the Xgboost model)  
---------- svt_speed_prediction.csv (prediction result by using the SVT model)  

## 2. How to run these models:

### 2.1 Xgboost model
          * open the Xgboost_model.ipynb
          * the required packages include: numpy, pandas, datetime, warnings, matplotlib, seaborn, sklearn, xgboost
          * run all the codes, the submission csv will be saved in the current working path

### 2.2 SVT model
          * open the SVT_model.ipynb
          * the required packages include: numpy, pandas, time
          * run all the codes, the submission csv will be saved in the current working path

## LICENSE
Please refer to [MIT License Copyright (c) 2020 YJiangcm](https://github.com/YJiangcm/MSBD_5001_kaggle/blob/master/LICENSE)
