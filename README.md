# Extremal learning

Neural networks allow us to model complex relationships between variables. We
show how to efficiently find extrema of a trained neural network in regression
problems. Finding the extremizing input of an approximated model is formulated
as the training of an additional neural network with a loss function that
minimizes when the extremizing input is achieved. We further show how to
incorporate additional constraints on the input vector such as limiting the
extrapolation of the extremizing input vector from the original training
dataset.

This is an instructional example of this approach using Tensorflow.
