# Replication results of "Crashworthiness Design of an Automotive S-Rail using ANN-Based Optimization to Enhance Performance and Safety"

The data required for training and constructing the surrogate model in this study are based on a Full-Factorial DoE, with the file 'Training Data.csv' containing both the Design of Experiments (DoE) and the response from each design configuration.

For the trained surrogate model, 'Surrogate Model.zip' contains the RSM model, as well as ANN models with ReLu, tanh, and sigmoid activation functions for EA, IPF, and Mass prediction. Note that replicating the ANN model using the provided 'Training Data.csv' may result in slight differences in weights and biases compared to those in the provided 'Surrogate Model.zip', as the ANN construction process involves randomly splitting the training and validation data.
