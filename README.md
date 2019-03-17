# CartPole-Balancing-using-Neural-Network

In this repository, we gonna build a simple neural network model to train our AI bot to learn itself to balance the cartpole.
 
 # Steps involved in building our AI bot :
 
 1.Import the Cartpole environment from gym
 
 2.Take random actions in the environment (in cartpole environment - only two discrete actions are allowed. They are:
 a) Move Left (0)
 b) Move Right (1)
 
 3.Then for these random actions, we need to store the "observation, rewards, done, info" and use this data as the training data for our neural network model.
 
 4. Now, after collecting the training data, it's now time to build the simple neural network with two dense layers and a fully connected layer.
 
 5. We then train the model with the training data we obtained in the previous step.
 
 6.After training, we render the environment to see how our AI bot performs balancing the cartpole.
