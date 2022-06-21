# Bankruptcy Prediction - Applications of Machine Learning (PRML, 2022)

## Description

- An organization wanted to predict bankruptcy prediction.
- They had historic bank data.
- Hence they needed to identify which set of parameters will lead to the bankruptcy of bank.
- We were required to use the training datasets to train the model to identify patterns that predict default and apply the model on the testing dataset.

## Dataset

- The dataset is about bankruptcy prediction. The bankrupt companies were analyzed in the period 2000-2012, while the still operating companies were evaluated from 2007 to 2013.
- The dataset contains 64 attributes with 2 classes. There were two files in the dataset train (containing 29847 samples) and test (containing 12780 samples).

## Evaluation 

- The evaluation metric for this competition is AUC score under ROC.
- AUC - ROC curve is a performance measurement for classification problem at various thresholds settings. ROC is a probability curve and AUC represents degree or measure of separability. It tells how much model is capable of distinguishing between classes. 
- Higher the AUC, better the model is at predicting 0s as 0s and 1s as 1s.

