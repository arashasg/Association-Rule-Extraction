# Association-Rule-Extraction

In this mini-project, I extracted association rules from the Amazon 
dataset using an implementation of the A priori algorithm. 
The A priori algorithm consists of 2 passes through the dataset. 
First, we find the most frequent items with a "support" above some
threshold. Afterward, we found the most frequent pairs of items 
bought frequently together. (each line of the dataset contains a 
customer order)

We used the Pyspark library and the map-reduce structure to do the commands in parallel.