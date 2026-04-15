# Forecasting Policyholder Retention in Motor Insurance using Generalised Linear Models and Random Forests
# Author: Saanya Singh

 This repository contains:
 - SaanyaSingh_FYP.ipynb : the final Jupyer Notebook containing data exploration, renewal simulation, and the three models
 - freMTPL2freq : policy-level data
 - freMTPL2sev : claims-level data
 - 
The raw datasets used are `freMTPL2freq` and `freMTPL2sev`, taken from the public freMTPL2 French motor third-party liability portfolio available on Kaggle.

 # Project overview
This project applies a logistic regression, GLM and Random Forest models to compare the methologogies when forecastin retention in motor insurance.
The datasets do not contain a renewal indicator, and so one is simulated using a reproducible process.

# To run this project:
- download this repository
- ensure both the datasets are in the same folder as SaanyaSingh_FYP.ipynb
- open Jupyter Notebook
- open SaanyaSing_FYP.ipnyb
- run all cells in SaanyaSing_FYP.ipnyb

Note: running the project will output 2 larger datasets, merged.csv and merged_with_renewal.csv, a new folder 'Outputs' will also be created in which tables and plots will be created. 
