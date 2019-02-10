# ClassificationAlgorithmsInR
Perform classification analysis in R 


This project uses the mHealth dataset from UCI machine learning repository to classify/predict activity types based on data such as acceleration, rate of turn, magnetic field orientation, ECG measurements, etc. The zip file downloaded from the repository contains 10 individual log files for 10 individuals, due to the constrain of my computer's memory, I will only use the first subject's data in this analysis. Therefore the results of my analysis might not be generalizable to all subjects. The goal of this project is to show how different classfication algorithms are used in R. 

Before we can apply any machine learning to our data, we need to preprocess the data first, so data preprocessing script should be run first. 

ML models included in this repository include:
   - Decision tree
   - Logistic regression
   - Support vector machine

Scripts are written as RMD files so that they can be converted to html output. 
