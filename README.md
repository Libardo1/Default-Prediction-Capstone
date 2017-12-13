Predicting Credit Card Default with XGBoost
==============================


This repository contains the documentation for my first capstone project at [Springboard](https://www.springboard.com/workshops/data-science-career-track).  My project applied gradient boosting tree models to predict consumer credit card default.   Specifically, I used a high-performance implementation of the gradient boosting algorithm called XGBoost to predict credit card default.  

------------

Keywords:  Risk management; Machine learning; Gradient boosting; XGBoost

------------


## Table of Contents

[Background](#background)  
[Objective](#objective)  
[Process Overview and Tech Stack](#process-overview-and-tech-stack)   
[EDA and Feature Engineering](#eda-and-feature-engineering)  
[Method](#method)   
[Results](#results)   
[Final Report](#final-report)   
[Next Steps](#next-steps)   
[GitHub Folder Structure](#github-folder-structure)  
[References](#references)  


------------

## Background

Machine learning techniques can be an important tool for financial risk management.  Performant and scalable machine learning models that are able to predict the probability of credit card default could bolster the risk management toolkits of credit scoring agencies and credit card originators.  




We trained and tested our gradient boosting model on the anonymized dataset of credit card holders used by Yeh & Lien (2009).  

...


------------

## Process Overview and Tech Stack

![tech-stack](reports/images/tech-stack.png)

------------

## EDA and Feature Engineering



Exploratory data analysis ("EDA")...


...

![eda-fig](reports/figures/EDA_Defaults_by_ratio_bapacl.png)


A more detailed description of the EDA and feature engineering process can be found in the [final report](#final-report) for this project.


------------


Capstone Project: Using machine learning to predict the probability of default of credit card clients.



------------

## Results

ROC Curve
![roc_curve](reports/figures/roc_curve.png)




------------

## Final Report

The final report for this project can be found [here](https://github.com/zkneupper/Default-Prediction-Capstone/blob/master/reports/Final-Report_Predicting-Credit-Card-Default-with-XGBoost.pdf).

------------

## GitHub Folder Structure

    ├── LICENSE
    ├── README.md          <- The top-level README for this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.    
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models
    │
    ├── notebooks          <- Jupyter notebooks.
    │
    ├── reports            <- Generated analysis as PDF reports and Jupyter notebooks.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │   └── images    
    │
    └── src                <- Source code for use in this project.
        ├── __init__.py    <- Makes src a Python module
        │
        ├── data           <- Scripts to download or generate data
        │   └── make_dataset.py
        │
        ├── features       <- Scripts to turn raw data into features for modeling
        │   └── build_features.py
        │
        └── models         <- Scripts to train models and then use trained models to make
            │                 predictions
            ├── predict_model.py
            └── train_model.py


------------

## References

1. [I-Cheng Yeh, and Che-Hui Lien. "The comparisons of data mining techniques for the predictive accuracy of probability of default of credit card clients." Expert Systems with Applications 36, no. 2 (2009)](https://pdfs.semanticscholar.org/1cac/ac4f0ea9fdff3cd88c151c94115a9fddcf33.pdf)
2. [Credit Card Default Data Set on the UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/default%20of%20credit%20card%20clients)
3. [Introduction to Boosted Trees](http://xgboost.readthedocs.io/en/latest/model.html)



------------
