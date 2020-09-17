# Online Hyper-Parameters optimization
Nowdays a Neural Network can be designed in many ways, and find the best configuration is becoming a hard task.

The configuration is a set of hyper-parameters, that describes the structures of the NN.

Usually the optimal configuration is found training the model with different configurations sampled from the configuration space and then select the best one wrt the test performance.

This method implies that every configuration is trained and tested and that the chosen one represents only the best of the proposed configurations and not the actual optimal.

This paper studies an algorithm to tunes the hyper-parameters from a given configuration, exploring the configuration space by itself and returning a better (and in the optimal region) configuration after the first training.
