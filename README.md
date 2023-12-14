# GAN-generator
# AI-Generated Fashion with GANs

This repository holds a Google Colab notebook that demonstrates the training of a Generative Adversarial Network (GAN) on the Fashion MNIST dataset. The goal is to generate new, synthetic images of fashion items that are indistinguishable from real, authentic data.

## Project Overview

The notebook includes the following sections:

- **Environment Setup**: Installation of all required dependencies, including TensorFlow, and setting up the GPU environment.
- **Data Loading and Preprocessing**: Utilizing TensorFlow Datasets to load and preprocess the Fashion MNIST dataset.
- **Visualization**: Displaying images from the dataset to understand the input data format.
- **Model Architecture**: Building the generator and discriminator models using TensorFlow's Keras API.
- **Training Loop**: Custom training steps for both the generator and discriminator, including loss calculation.
- **Callbacks**: Saving model checkpoints to Google Drive and generating sample images after each epoch.
- **Loss Plotting**: Visualizing the training loss for both the generator and discriminator.
- **Sample Generation**: Generating and displaying new fashion items using the trained generator.

## Usage

To use this notebook:

1. Open the notebook in Google Colab.
2. Run all the cells to install the dependencies, prepare the dataset, and start the training process.
3. Monitor the training progress through the generated loss plots and sample images.

## Models

The GAN consists of two primary components:

- **Generator**: Takes a random noise vector as input and generates synthetic images.
- **Discriminator**: Tries to distinguish between real images from the dataset and fake images produced by the generator.

## Results

After training, the GAN is capable of generating new images that reliably resemble the fashion items from the Fashion MNIST dataset. Sample images are saved in the repository for reference.
