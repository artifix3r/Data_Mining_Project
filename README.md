# Data_Mining_Project
Data Mining project with pattern mining 
Problem description 
The project aims at playing with the dataset ‘CAR’ using data mining techniques. The dataset CAR is car evaluation database that contains examples of car detailed over 6 attributes and
one class. The six input attributes: buying, maint, doors, persons, lug_boot, safety. The dataset contains for each car a class that rates the acceptability of the car {unacceptable, acceptable,
good, very good }. The dataset suffers from unbalanced classes.

## The first task is :
  In this part, you have to preprocess taking into consideration the type of used data (integers,text) to mine useful knowledge. To do so, you may generate as a first step frequent patterns that
  have a frequency greater than or equal to the threshold fixed by the user using one of the pattern mining algorithms. A comparative and extensive comparison of several algorithms should be
  made additionally to parameter tuning experiments (threshold value, pattern length, class inclusion). You may consider using the pattern mining librairy SPMF1 (the API or the developer mode) for
  the mining and the evaluation task.
## Second one is :
 In this part, you to have to consider the patterns or/and association rules mined from the first task and develop a model to classify a new car.
 
 For the first task we use spmf with Apriori algorithm 
 
 And for the second task we use Random Forest Algorithm for classificate datas . 
 
  
