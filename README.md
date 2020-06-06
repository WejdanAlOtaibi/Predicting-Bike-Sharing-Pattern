# Predicting-Bike-Sharing-Pattern
# First Neural Network

First Neural Network I built is for predicting bike sharing pattern. 

I was provided with a dataset that I was supposed to analyze along the way and train the model according to. 

Due to the holidays season the model performed poorly between 22 Dec and 31 Dec, because people tend to rest more instead of using bikes. Basically, we don't have enough data for holidays season in our training data. So the model treats those days like regular days. If we will have more data than model should catch this behavior.


The code of the project consisted of:
1. Sigmoid activation function
2. Forward Pass 
3. Run method: for producing the desired regression output for the neural network 
4. Backward Pass: updating the weight change 
5. Updating both of the input-to-hidden and hidden-to-output weights 
6. Hyperparameters: the number of epochs is chosen such the network is trained well enough to accurately make predictions, but it’s not overfitting to the training data.
7. The learning rate is chosen such that the network successfully converges, but is still time efficient. 

For the dataset go to Deep Learning repository.
