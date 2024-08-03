# Data Mining Projects

This repository contains various data mining tasks, focusing on different techniques and methodologies. Each project addresses specific challenges and employs different datasets and algorithms.

## Table of Contents

1. [Project 1: Curse of Dimensionality and PCA](#project-1-curse-of-dimensionality-and-pca)
2. [Project 2: Decision Trees and Model Overfitting](#project-2-decision-trees-and-model-overfitting)
3. [Project 3: Text Classification and Digit Recognition](#project-3-text-classification-and-digit-recognition)
4. [Project 4: Clustering](#project-4-clustering)
5. [File Structure](#file-structure)

## Project 1: Curse of Dimensionality and PCA

### P1-1. Curse of Dimensionality
- **(a)** Generate 1000 points following a uniform distribution under a given dimension. Compute the difference between the max and min distance between any pair of points.
- **(b)** Repeat for dimensions ranging from 2 to 50.

### P1-2. The Iris Dataset
- **(a)** Data Visualization: Duplicate the specified scatter plot using the Iris dataset.
- **(b)** Find the best discretization for petal length and petal width to separate Iris data. Plot and evaluate how well each flower type is separated.

### P1-3. Principal Component Analysis (PCA)
- **(a)** Plot samples using Sepal Length and Sepal Width from the Iris dataset.
- **(b)** Apply PCA to reduce the dataset from 4 dimensions to 2 and compare the results with the figure from (a). Discuss the effectiveness of dimensionality reduction.

## Project 2: Decision Trees and Model Overfitting

### P2-1. Decision Tree
- **(a)** Develop a decision tree classifier for the Iris dataset. Use 5-fold cross-validation, balance the training dataset, and train with 120 samples. 
- **(b)** Show the confusion matrix and plot the decision tree.

### P2-2. Model Overfitting
- **(a)** Generate datasets as described and plot them.
- **(b)** Train decision trees with varying numbers of nodes. Plot and analyze training and testing errors to illustrate model underfitting and overfitting.

### P2-3. Text Document Classification
- **(a)** Load the 20 newsgroups dataset with specified categories. Print the number of documents and attributes in the training and test datasets.
- **(b)** Develop a decision tree classifier for text document classification and show the confusion matrix.

## Project 3: Text Classification and Digit Recognition

### P3-1. Revisit Text Document Classification
- **(a)** Load specified categories from the 20 newsgroups dataset.
- **(b)** Build classifiers using SVM, Naive Bayes, K-nearest neighbors, Random Forest, and AdaBoost. Compare classification accuracy.

### P3-2. Recognizing Handwritten Digits
- **(a)** Develop a multi-layer perceptron classifier to recognize handwritten digits with accuracy greater than 90%.
- **(b)** Show the confusion matrix and compare results with SVM.

### P3-3. Nonlinear Support Vector Machine
- **(a)** Generate 2-class data points and develop a nonlinear SVM classifier.
- **(b)** Plot data points and decision boundaries.

## Project 4: Clustering

### P4-1. Hierarchical Clustering Dendrogram
- **(a)** Generate random data points and use Agglomerative Clustering to cluster them.
- **(b)** Plot a dendrogram using different linkage methods.

### P4-2. Clustering Handwritten Digits
- **(a)** Cluster the handwritten digits dataset using K-Means and DBSCAN. Optimize parameters and evaluate methods.

### P4-3. Clustering Structured Dataset
- **(a)** Generate a Swiss roll dataset and use AgglomerativeClustering and DBSCAN for clustering.
- **(b)** Plot the clustered data in 3D figures and compare results.

## File Structure

- `Project 1.ipynb`: Jupyter Notebook for Project 1 tasks.
- `Project 2.ipynb`: Jupyter Notebook for Project 2 tasks.
- `Project 3.ipynb`: Jupyter Notebook for Project 3 tasks.
- `Project 4.ipynb`: Jupyter Notebook for Project 4 tasks.
- `README.md`: This file.
