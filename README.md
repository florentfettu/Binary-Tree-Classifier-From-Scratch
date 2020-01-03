# Binary Tree Classifier From Scratch

## Description
The aim of this project is to develop from scratch an algorithm in python without using any third party package, or as little as possible. We decided to build our own binary tree classifier.
 
## Scope of the project
* 3 functions were implemented:
    1. meilleur_split: Find the best split
    2. construction_arbre: Build the tree
    3. Prediction: Predict a new observation
* 3 hyperparameters were implemented (maximum depth, impurity criterion, minimum information gain)

## Speed and performance test of our tree versus sklearn's tree
* Slower than sklearn tree to predict 1 million observations
* Better accuracy than sklearn's tree on the Iris dataset
