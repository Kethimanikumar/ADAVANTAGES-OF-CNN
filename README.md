Originally Answered: What are the advantages of convolutional neural network compared to a simple neural network from the theoretical and practical respective?
Convolutional Neural Networks take advantage of local spatial coherence in the input (often images), which allow them to have fewer weights as some parameters are shared. This process, taking the form of convolutions, makes them especially well suited to extract relevant information at a low computational cost.


You could try to use CNNs on data with no local coherence, such as shuffled images, but that would give poor results as the network wouldn’t be able to identify spatial patterns.
