# Data Analytics
CZ4032 - Data Analytics &amp; Mining

## Assignment 1
#### 1. Select a topic/task from any of the list below
- Clustering
- Link Analysis
- Similarity Search
- Graph Neural Network
- Graph Clustering & Community Detection
- Recommender System
#### 2. Select at least 2 algorithms, implement and review the 2 methods (Weaknesses, Strengths, Parameter settings, Key factors which affects the performance)

### What was done:
- Chose to implement and review Nearest Neighbour Approximation.
- Implemented 3 Approximation algorithm
  1. Local Sensitive Hashing
  2. Product Quantization
  3. Inverted File Index
- Compared each Algorithms with each other and Linear Search

![image](https://github.com/titim789/Data_Analytics_Project/assets/89781573/9813f4be-1945-4317-8336-356f47acc2dd)

## Assignment 2
#### 1. Implement the Apriori Algorithm to mine Frequent Itemsets
#### 2. Use 3 Datasets to run Apriori algorithms with different min-support thresholds (1 of the dataset has to be at least 4GB)
- It is mandatory that the implemented Apriori Algorithm is disk based able to handle any size dataset
#### 3. Use the frequent itemsets as features to do clustering with any 2 clustering algorithms and review its performance
#### 4. Figure out an algorithm for improving the performance fo the methods in Task 3. Give the Psuedocode, report and evaluate the results

### What was done:
- Implemented disk-based Apriori
- Tested it with 3 datasets
#### ![image](https://github.com/titim789/Data_Analytics_Project/assets/89781573/8e85ef07-2ccd-4655-aecd-1d316a7dbf2e)
- Chose k-means and hierarchical clustering to cluster the dataset with frequent itemsets as features
![image](https://github.com/titim789/Data_Analytics_Project/assets/89781573/8f99c350-9941-47b2-b2cb-dddfb06da2c6)
- Suggested 2 Improvements
  1. TF-IDF Based Candidate Selection
  2. Clustering with Parallel Programming

