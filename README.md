# Application oriented spawning of neural networks from a base neural network

A neural network is a powerful computational data model that is able to capture and transmit,  represent complex input/output relationships. Precisely, ANN is an information processing paradigm that is inspired by the way biological nervous systems, such as the brain, process information. 
Usually , the structure of the hidden layer, selection of activation function, computational time
are the issues faced while devising an ANN. 
Hence, we have focused on the idea of developing a neural network that would serve as a base and would automatically spawn neural networks based on application requirements of user.

# Outcome
The algorithm focuses on providing a feasible neural network which assigns an appropriate activation function and structures the schema of hidden layer according to user require ments. Thus, generating an appropriate neural network for the user.

# Input
Input is in the form of Graph based P - Class Problems, such as finding a minimum spanning tree for a given graph matrix using Prim's or Kruskal's algorithm. 

# Structure and Modelling
The developed model of the base neural network is a convolutional neural net.

# Dataset
Training data sets are in the form of undirected weighted graph matrices.

# Summary
The basic moto is to spawn a child neural network. Precisely, to evolve a structure (number of neurons in input layer, structure of hidden layer) of child neural network using the base neural network.
The base neural network classifies the input matrices as dense or sparse.
Considering the sparsity of the matrix, the  base neural network will spawn a child neural network.
Prim's algorithm is selected if the matrix is dense otherwise,  Kruskal's algorithm is used to find the minimum spanning tree  i.e. the child neural network will give the result in form of MST.
For spawning the child we are trying to apply various genetic algorithms and concepts of evolutionary programming. 

![promisechains](https://user-images.githubusercontent.com/20223307/30606122-41f8bfa0-9d8e-11e7-94c4-737c0d5aad39.jpg)
