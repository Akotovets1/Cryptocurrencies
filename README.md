# Cryptocurrencies
Unsupervised Machine Learning and Cryptocurrencies


## Overview
The investment bank, Accountability Accounting, is interested in offering a new cryptocurrency investment portfolio to its clients. The management needs assistance in determining which cryptocurrencies should be offered.  So they requested a report that includes what cryptocurrencies are on the trading market and if they could be grouped to create a classification system for this new investment.

The data getting from the company needed to be cleaned in order to fit the machine learning models, and because there isn't a known output, unsupervised machine learning was used.

For grouping the cryptocurrencies, a clustering algorithm was used and the data was visualized so the result could be shared with the management of the company.


## Results

### The imported DataFrame before cleaning:

![1](https://github.com/Akotovets1/Cryptocurrencies/blob/main/Images/01.png)

### The list of cryptocurrencies after cleaning:

![2](https://github.com/Akotovets1/Cryptocurrencies/blob/main/Images/02.png)

### K-means Clustering Algorithm, Elbow Curve:

![3](https://github.com/Akotovets1/Cryptocurrencies/blob/main/Images/03.png)
An elbow curve was produced in order to find the best value for K. This would be used to determine the number of clusters that should be used in the K-Means clustering algorithm. According to the elbow curve, k=4

### 3D Scatterplot with Clusters, Visualizing Tradable Cryptocurrencies:

![4](https://github.com/Akotovets1/Cryptocurrencies/blob/main/Images/1.png)
The unsupervised machine learning algorithm PCA was used to reduce the dimensions of the cryptocurrency components to three principal components. 
3D scatter chart shows the cryptocurrency dataset in four clusters.

### Tradable Cryptocurrencies:

![5](https://github.com/Akotovets1/Cryptocurrencies/blob/main/Images/2.png)

2D scatter chart shows each cryptocurrency from the dataset as it related to total coins mined and total coin supply.

