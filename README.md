# Breast Cancer Prediction using Genomic Data #

### Here in this project I have implemented machine learning algorithms to predict _Breast Cancer_ in patients using their _Gene Expression Data_ ###

I have implemented ___3___ machine learning Models:
 1. Support Vector Machine
 2. Randomn Forest
 3. Decision Tree

  Model                   | Accuracy (%)
  :---------------------: | :-----------:
  Randomn Forest          | 99.07
  Decision Tree           | 97.53
  Support Vector Machine  | 97.22

* The Gene Expression dataset is attached as upscale.csv
  * There are total ___21 Genes in the Dataset___
  * The first column represent the ___patient ID___
  * The other 21 columns represent each gene expression data
  * And the last column represent the result i.e. if patient has Breast Cancer then ___1___ and if he/she does not have Breast Cancer then ___0___ 

* I have plotted the ___Confusion Matrix___ for each Model
* Also I have implemented ___Eli5___ (Explain Like I am 5) inorder to get the feature importance or contribution of each Gene
