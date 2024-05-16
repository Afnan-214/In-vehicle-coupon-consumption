# In-vehicle-coupon-consumption
A team project to apply data computation and analysis concepts starting with dimention reduction techniques,to model building and hyper tuning. this project was conducted considering the concepts of appling these techniques and how it's results' impact on the business.
> *The notebook is structured as a full detailed report.*
## Overview
The dataset contain 25 feature (categorical) describe different driving scenarios and class target 'Y' which consistent of (1,0) <br>
The data is supervised, the goal of using this data to predict whether the driver will accept (consume) the coupon or not (accept take value (1) and not accept take value (0)), can identify the driver accept or reject the coupon based on the features.<br>
* First:
Need to conduct data exploration to determine which features depend on whether a coupon is accepted or not.
* Second:
Need to build a model to classify the driver will accept the coupon or not, So use SVM for classification help to predict Whether or not to accept the coupon.
## Project phases 
1. Data cleaning
2. Data exploration was separeted into 4 section based on the features category and then some analytical questions the combine multiple feature to extract more complex relations.
3. Feature selection & Feature extraction: the techniques were choosen based on the features and the data normality.
4. Model building and hypertunning: using random search to test different ranges for the parameters and extract a better model
5. Model evalution: using different metrices (e.g. precision, recall,f1-score), ROC graph and confusion matrix to check how well the model actually perform.
