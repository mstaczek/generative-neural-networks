# Generative Neural Networks - homework solutions

This repo contains solutions to homework assignments for the course about Generative Neural Networks for the Sciences at the University of Heidelberg.

Co-authored with [Agata Kaczmarek](https://github.com/kaczmareka)

## Contents 

Below are short descriptions of what each assignment was about.

### Homework 1

Implement and use various models to learn and generate [two-moons dataset from sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_moons.html) and [digits dataset from sklearn](https://scikit-learn.org/stable/auto_examples/datasets/plot_digits_last_image.html): 
- 2D histogram
- a single gaussian distribution
- a Gaussian mixture model (GMM)
- a kernel density estimator (KDE)

Maximum mean discrepancy (MMD) is used as a metric to compare the generated data with the original dataset.

### Homework 2

Implement a simple autoencoder. Experiment with hyperparameters such as bottleneck size. Add MMD loss to make the codes dimension similar to gaussian distribution and sample from it to generate new data. 

Use [two-moons dataset from sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_moons.html) and [digits dataset from sklearn](https://scikit-learn.org/stable/auto_examples/datasets/plot_digits_last_image.html).

### Homework 3

Implement an Invertible Neural Network, called RealNVP. Experiment with different numbers of Coupling Blocks and other hyperparameters. Implement a conditional version of RealNVP and a version with an artificial bottleneck. Compare behaviour of these models.

Use [two-moons dataset from sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_moons.html) and [digits dataset from sklearn](https://scikit-learn.org/stable/auto_examples/datasets/plot_digits_last_image.html), but also [digits from torch MNIST dataset](https://pytorch.org/vision/main/generated/torchvision.datasets.MNIST.html).