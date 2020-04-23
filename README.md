# Auto Insurance Claim Fraud Detection


We are developing auto insurance fraud detection identification for insurance using random forest, gradient boosted trees and artificial neural network.  Insurance claims fraud has cost insurance industry over $40B and cost family $400-$700 of increased premium each year according to FBI.GOV.  


Tree algorithm gives us feature importance ranking which is easy for business to understand. While both random forest and gradient boosted trees gave good results, gradient boosted tree algorithm achieve 1% higher accuracy and great recall over 97% which is well above 85% from random forest. ANN is a lot worse compared to both random forest and gradient boosted trees. 


Steps for the tree algorithm:
1.	Import data and do data cleaning. 
2.	Oversample and make data balanced.
3.	Run both tree algorithms using TensorFlow framework
4.	Try to optimize hyperparameters to get best results by tuning tree numbers and depth of trees.  
5.	Feature importance from tree algorithm with individual samples to get better understand the business logics. 
