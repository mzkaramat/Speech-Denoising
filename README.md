# Speech Denoising Using Deep Learning

A fully connected network with 2 hidden layers and 1000 hidden units each is used for speech denoising.
For the two hidden layers I have used tanh activation functions. (Referred from:- http://paris.cs.illinois.edu/pubs/liu-interspeech2014.pdf). Apart from this, I have used Xavier initialization for weights, batch normalization and Adam Optimizer.
For the last layer since we are required to output non negative, I have opted for relu activation function. Applying 20% dropouts during training helped improve the recovered test signal.
