# PVAE
Replication of the approach suggested in this paper: Poisson Variational Autoencoder by Vafaii et al 2024
https://arxiv.org/abs/2405.14473 
The paper introduces a new type of Variational Autoencoder (VAE) called the Poisson Variational Autoencoder (P-VAE). This model is designed to more closely mimic how biological neurons process information. Traditional VAEs use continuous variables, but P-VAE uses discrete variables that represent neuron spike counts, making it more biologically realistic.

We generate a dataset of grayscale images, each containing a single shape: circle, square, or triangle. The goal is to train the P-VAE to encode and decode these images, learning to represent the shapes efficiently.

We load this dataset in the training script to train the P-VAE. 

Then we train the P-VAE on this dataset by integrating the DataLoader into the training loop.

