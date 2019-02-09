# ClassificationAlgorithmsInR
Perform classification analysis in R 


This project uses the mHealth dataset from UCI machine learning repository to classify/predict activity types based on data such as acceleration, rate of turn, magnetic field orientation, ECG measurements, etc. The zip file downloaded from the repository contains 10 individual log files for 10 individuals, due to the constrain of my computer's memory, I will only use the first subject's data in this analysis. Therefore the results of my analysis might not be generalizable to all subjects. The goal of this project is to show how different classfication algorithms are used in R. 

Below is more introduction about the dataset: 
   
L1: Standing still (1 min) 
  
L2: Sitting and relaxing (1 min) 
  
L3: Lying down (1 min)
  
L4: Walking (1 min) 
  
L5: Climbing stairs (1 min) 
  
L6: Waist bends forward (20x) 
  
L7: Frontal elevation of arms (20x) 
  
L8: Knees bending (crouching) (20x) 
  
L9: Cycling (1 min) 
  
L10: Jogging (1 min) 
  
L11: Running (1 min) 
  
L12: Jump front & back (20x) 
    
       
The meaning of each column is detailed next: 
   
Column 1: acceleration from the chest sensor (X axis) 
  
Column 2: acceleration from the chest sensor (Y axis) 
  
Column 3: acceleration from the chest sensor (Z axis) 
  
Column 4: electrocardiogram signal (lead 1) 
  
Column 5: electrocardiogram signal (lead 2) 
  
Column 6: acceleration from the left-ankle sensor (X axis) 
   
Column 7: acceleration from the left-ankle sensor (Y axis) 
  
Column 8: acceleration from the left-ankle sensor (Z axis) 
  
Column 9: gyro from the left-ankle sensor (X axis) 
  
Column 10: gyro from the left-ankle sensor (Y axis) 
   
Column 11: gyro from the left-ankle sensor (Z axis) 
  
Column 13: magnetometer from the left-ankle sensor (X axis) 
  
Column 13: magnetometer from the left-ankle sensor (Y axis) 
  
Column 14: magnetometer from the left-ankle sensor (Z axis) 
  
Column 15: acceleration from the right-lower-arm sensor (X axis) 
  
Column 16: acceleration from the right-lower-arm sensor (Y axis) 
  
Column 17: acceleration from the right-lower-arm sensor (Z axis) 
  
Column 18: gyro from the right-lower-arm sensor (X axis) 
   
Column 19: gyro from the right-lower-arm sensor (Y axis) 
  
Column 20: gyro from the right-lower-arm sensor (Z axis) 
  
Column 21: magnetometer from the right-lower-arm sensor (X axis) 
  
Column 22: magnetometer from the right-lower-arm sensor (Y axis) 
  
Column 23: magnetometer from the right-lower-arm sensor (Z axis) 
     
Column 24: Label (0 for the null class)   
