# Machine_Learning_NLP_with_RNN-Based_Autoencoders
In this assignement, we will practice the application of deep learning to natural language processing. We will be
working with a subset of Reuters news headlines that are collected over 15 months, covering all of 2019, plus a
few months in 2018 and in a few months of this year.
In particular, we will be building an autoencoder of news headlines. The idea is similar to the kind of image
autoencoder: we will have an encoder that maps a news headline to a vector embedding, and
then a decoder that reconstructs the news headline. Both our encoder and decoder networks will be Recurrent
Neural Networks, so that we have a chance to practice building
a neural network that takes a sequence as an input
a neural network that generates a sequence as an output
This assignment is organized as follows:
Question 1. Exploring the data
Question 2. Building the autoencoder
Question 3. Training the autoencoder using data augmentation
Question 4. Analyzing the embeddings (interpolating between headlines)
Furthermore, we'll be introducing the idea of data augmentation for improving of the robustness of the
autoencoder, as proposed by Shen et al [1] in ICML 2020.
