# Deep Neural Net Implementation 
------------------------------------  

For this neural net I will be laying out the structure and architecture of a neural network using the NumPy library.  
The goal is to study the architecture of an L-layerd neural net and formulate the forward pass and backward pass functions and to successfuly deploy gradient descent and figure out backpropagation .  

### Scope
------------------------------------  
I wont be going into network optimization or hyperparameter tuning in this one . The goal is to simply fit the data by deploying multiple layers of neurons and to visualize how the non linearity brought by the various activations in different hidden layers can effectively fit the data of the given problem .  
The goal here is to learn the basic behaviour of perceptrons and figure out a way to optimize them.  
Follow up on this project will be a complex neural net with gpu accelerated vector computation and use of optimizers. 

## Architecture:  
![Alt text](images/1694464170086.jpg)  
This is the architecture of a deep neural network.  
The implementation involoves understanding the problem and vectorizing the inputs properly.  
After that it's important to initialize our parameters ( Weights and biases ).  
Weights and biases will simply linearly transform the vectors .