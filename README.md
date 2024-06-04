# Using Machine Learning to Identify Blue Straggler Stars

## Abstract
The presence of blue straggler stars (BSSs) in open clusters (OCs) presents an opportunity to study star formation and cluster dynamics. Our paper investigates the feasibility and application of identifying BSSs solely based on color indices, specifically through utilizing a Decision Tree, Support Vector, and Logistic Regression. Using machine learning, we demonstrate that a star's BSS candidacy can be predicted with approximately 80\% accuracy based solely on its color indices.

## Description
Python script that identifies BSSs from their color indices using machine learning. We used three classifiers: Decision Tree, Support Vector, and Logistic Regression. We limited the number of non-blue straggler stars to equal the number of BSSs to ensure equal sample sizes. Each model is run 500 times, each run using different random seeds for our sample selection and for our train-test split, to achieve better results.

## Data Sources
The data used to train these models is sourced from data collected in this paper:

Li, Chunyan, Zhong, Jing, Qin, Songmei, & Chen, Li.67  
2023, A&A, 672, A81,68  
doi: 10.1051/0004-6361/20224499869  

Their CDS link can be found here:  
https://cdsarc.cds.unistra.fr/viz-bin/cat/J/A+A/672/A81#/seealso  

## Notes
GitHub cannot preview ipynb files. Instead, the jupyter notebook file of the code can be viewed here: https://nbviewer.org/github/yuvraj-sahu/machine-learning-bss-identification/tree/main/

