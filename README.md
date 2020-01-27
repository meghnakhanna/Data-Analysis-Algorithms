# Data-Analysis-Algorithms
Compilation fo data analysis algorithms
  
  
 # Project's aim
# Part A: Solve a document clustering problem using unsupervised learning algorithms(i.e.,soft and hard Expectation Maximization)for document clustering.
 
Based on the assumption that documents with similar text are related and should belong to one corpus.So in this task we are prvoide with a collection of documents and are clustered into genres/groups/clusters of documents using the text, where the documents are treated as a bag of words whcih belong to some dictionary A. Initially all documents are assigned a random probability of a document belonging to a certain cluster and the probability keeps on increasing as more data is processed.
We calculate the expectation of the log-likelihood since we do not have complete data, we only have observed data X and latent variables Z which are the potential themes for the documents to be clustered into.

It has parameters: Cluster proprotion, word proportion and  number of clusters. 

The aim is to maximize the likelihhod, this is mixture modelling for document modelling. 


 
 
# Part B: Apply a 3-layer Neural Network on a synthetically generated data to compare its performance with a Perceptron.


 
 
# Part C: Self Taught Learning
  In this part, I implemented the self-taught learning for a 3 layer Neural Network using an Autoencoder and analysed the   reconstruction error rate for the self-taught learning model with the increase in layers of the neural net.
  
Here we use neural networks as an unsupervised learning model where it used as an autoencoder which is basically feed forward neural netwrok where the hidden units are less than the input units(the output units are the same number as the input units) and the model is reconstructing itself with minimum reconstruction error. The model is basically training itslef to build itself so that it can be used as an unsupervised learning model.


Used for dimensionality reduction.

# Datasets

*Task 2A.txt-  Part A*

 *Task 2B_test.csv and Task2B_train.csv - Part B*

 *Task 2C_labeled.csv, Task2C_unlabeled.csv and Task2C_test.csv - Part C*


# Setup
 
 Using Anaconda


**Add a R kernel to your jupyter notebook by building a new environment in your anaconda navigator and selecting R kernel and python and launching that virtual environemnt.**

**Using the command line/terminal for Mac and linux users**

# Commands

Ctrl-Alt-T - shortcut to open terminal

Commands available on:

https://github.com/IRkernel/IRkernel
