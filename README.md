# stunning-telegram
This repository contains 2 scripts created by me with full data analytics workflow. These scripts are my submissions for assessment in the 7313 - Data Science Analytics course at Stockholm School of Economics.

Please note that if Github is unable to load the notebooks, use https://nbviewer.jupyter.org/ instead! There is no need to install it. Direct link: https://nbviewer.jupyter.org/github/AlanRebane/stunning-telegram/tree/main/

## Purpose
I created this repo to show how I would approach a business case with data analytics that involves modelling. The accompanying 2 scripts include:
- Getting the data from the SQL database
- Cleaning and preparing a dataset for modelling (+ creating a data cleaning pipeline)
- Predicting an outcome variable using different models
- Estimating a USD value impact based on model accuracy
- Using neural networks for modelling

## Background on the business case
Toy Storey sells toys online and offers shipping or pick-up globally. They offer a subscription service (a surprise box of toys delivered at home every month). Throughout the last six year, ten percent of customers have been invited to try for a free first month. Offering the first month, including approaching customers and setting up the service package, is quite costly (40$). All consumers that are approached, subscribe to the service. For those customers who retain their service contract, the subscription program is very profitable (20$ margin per month, starting second month).

![thomas-and-friends-2435542_640](https://user-images.githubusercontent.com/63585199/124383543-af2c6880-dcd5-11eb-89e7-dd5fa3cb0ba0.jpg)

*Image by Nathan Legakis from Pixabay*

## Notes on the scripts
modelling.ipynb - This jupyter notebook file shows how I use 5 different models (logistic regression, decision trees, SVM, an ensemble method based on all three, and random forests) to predict a boolean outcome variable (churn).
- The dataset is available for download on my Google Drive: https://drive.google.com/file/d/1l0_UaxUb8mH8B_4NSEFTko9FTzzz9Eba/view?usp=sharing

modelling_nn.ipynb - This jupyter notebook file shows how I use neural networks to predict a boolean outcome variable (whether a customer is exclusive to ToyStorey or not).
- https://drive.google.com/file/d/1Ct_25CQT8-37Aunsss7UtIgY94YNuS-a/view?usp=sharing


The datasets are fictitious, though they attempt to replicate a real dataset (i.e. names and numbers are changed).
