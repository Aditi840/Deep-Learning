# Deep-Learning

# Introduction to Generative Modeling with GANs

This repository contains code for building and training Generative Adversarial Networks (GANs) to generate anime character faces using the Anime Face Dataset.

## Project Overview

Generative modeling is an unsupervised machine learning task that involves discovering and learning the patterns in input data to generate new examples similar to the original dataset. In this project, we utilize GANs, which consist of two neural networks: a Generator and a Discriminator.

- **Generator**: Creates new data samples resembling the training data.
- **Discriminator**: Distinguishes between real and generated samples.

### Key Features

- **Anime Face Dataset**: A dataset containing over 63,000 cropped anime faces.
- **GAN Architecture**: Utilizes convolutional neural networks (CNNs) in both the generator and discriminator.
- **Training on GPU**: Includes utilities for seamless GPU training.
- **Image Normalization and Transformation**: Preprocessing steps to normalize and transform images for efficient training.
- **Visualization**: Utilities to visualize generated images during training.

## Installation

To run this project, you need Python installed on your machine along with several Python libraries.

### Required Libraries

- PyTorch
- torchvision
- matplotlib
- opendatasets
- Jovian

You can install the required libraries using:

```bash
pip install torch torchvision matplotlib opendatasets jovian
