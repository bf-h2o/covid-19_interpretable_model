# covid-19_interpretable_model

This work is based on the data and Analysis of Li-Yan et al., 2019 published in Nature Machine Intelligence. 
https://www.nature.com/articles/s42256-020-0180-7#MOESM3. This article used a gradient boosting method implmented in python.

This time, the rapid glmnet model is used to identify the factors that are the most important to predict the clinical outcome of patients affected by the COVID-19 based on several biomarkers.

The top biomarkers are selected to build a decision-tree providing a 91% accuracy in clinical outcome determination with a good temporal window. 

The results are similar to the ones obtained by Li-Yan et al. We thank them for making their data accessible to the scientific community.
