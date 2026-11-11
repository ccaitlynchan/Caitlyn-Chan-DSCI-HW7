# DSCI 552 Homework 7

Caitlyn Chan

## Contents
- `notebook/DSCI_552_HW_7.ipynb`: solutions
  1. Multi-class, multi-label classification with SVMs (Gaussian kernel, L1-penalized, L1 + SMOTE)
  2. K-means clustering with Monte Carlo simulation (50 runs)
  3. ISLR 12.6.2
- `data/`: the Anuran Calls (MFCCs) data (`Frogs_MFCCs.csv`)

## Running
Open the notebook from the `notebook/` folder; it reads the data from `../data/`.
Requires numpy, pandas, matplotlib, scipy, scikit-learn and imbalanced-learn.
Note: the full notebook takes about an hour to run (grid searches + 50 k-means runs).
