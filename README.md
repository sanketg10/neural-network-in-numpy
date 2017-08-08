# neural-network-in-numpy

The ipython notebook goes through a step by step implementation of a neural network from first principles. It uses Numpy in Python to build forward pass as well as backpropagation for a 2 layer neural network. It was great to learn the basics of implementation esp. backpropagation as it is not an easy concept to understand. 
Here are the steps: 
1. Prepare the data in numpy arrays. Have features `X` and targets `y` ready. This step needs pre-processing of data.
2. Build an API for `train` and `run`. Training will have backprop to get all the weights ready. Running will just have forward pass to get the output. 
3. Have unit test to test it for a single sample. 
4. Tune *hyper-parameters* such as learning rate, epochs and hidden neurons to trade-off CV and train error using learning curves. 
5. Fix the hyper-parameters and train the model. Look at the output and plot it with labels. Reiterate if necessary. 
