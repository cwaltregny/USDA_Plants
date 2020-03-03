# Clustering Plants based on US regions 

## Introduction

The USDA Plants database provides standardized information about the vascular plants, mosses, liverworts, hornworts, and lichens of the U.S. and its territories.

The goal of this project will be to cluster the plants based on the regions where they are present; we are in an unsupervised learning scenario.

## Dataset

The dataset is composed of 34781 instances of plants names, associated with the states names where they can be found in. The dataset can be found [here](https://archive.ics.uci.edu/ml/datasets/Plants) and is taken from -- _USDA, NRCS. 2008. The PLANTS Database (31 December 2008). National Plant Data Center, Baton Rouge, LA 70874-4490 USA_ --

## Method

We'll divide our project into 4 steps:
1. Problem Description
2. Data Analysis and Preparation
3. Modelling and Evaluation
4. Conclusion

Instead of just trying different number of clusters to see which one should be used, we'll try to assess the optimal number using the Elbow method (for the KMeans algorithm) or by plotting the dendrogram (for the hierarchical agglomerative one).
