# Customer Segmentation Using K-Means Clustering

### Introduction
This project uses customer demographic, transactional, and behavioral data from Kaggle and can 
be found [here](https://www.kaggle.com/datasets/ravalsmit/customer-segmentation-data/data). The CSV file can be downloaded and read into python. The dataset contains 20 
total features ranging from age, gender, and marital status to the location of the customer and 
their policy information. 
This project consists of the following sections:
 - Data Exploration
 - Preprocessing
 - Deploy K-Means Clustering Algorithm 
 - Analyze Dataset Using New Clusters

### Data Exploration
Explore the dataset using Jupyter Notebook.

### Preprocessing
Clean date formats for purchase history and drop rows that are not affiliated with the specific 
location or policy type. Drop non-numerical columns which leaves the transactional data for the 
clustering algorithm. Scale the numerical features using sklearn’s preprocessing package. 

### Deploy K-Means Clustering Algorithm
Use K-Means algorithm from sklearn’s clustering package to calculate sum of squared distances 
and plot elbow plot to determine the optimal number of clusters. Fit clustering algorithm to data 
with optimal number of clusters. 

### Analyze Dataset Using New Clusters
Analyze dataset using new clusters created for the customers.
