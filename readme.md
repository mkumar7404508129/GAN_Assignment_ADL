# GAN Assignment - Advanced Deep Learning

This repository contains implementations of various Generative Adversarial Networks (GANs) using PyTorch. The models include:

1. **Standard GAN**
2. **Wasserstein GAN (WGAN)**
3. **Spectral Normalization GAN (SNGAN)**
4. **Convolutional GAN (CNN-GAN)**

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Dataset](#dataset)
- [Usage](#usage)
- [Training](#training)
- [Results](#results)
- [License](#license)

## Introduction

Generative Adversarial Networks (GANs) are a class of machine learning frameworks designed by Ian Goodfellow and his colleagues in 2014. They consist of two neural networks, a generator and a discriminator, that compete against each other. The generator creates fake data, while the discriminator evaluates its authenticity.

This project implements several variations of GANs to generate images from the MNIST dataset.

## Requirements

To run the code, you need to have the following libraries installed:

- Python 3.x
- PyTorch
- torchvision
- matplotlib
- pandas
- torch-summary

You can install the required libraries using pip:

```bash
pip install torch torchvision matplotlib pandas torch-summary
```

## Dataset

The models are trained on the MNIST dataset, which consists of handwritten digits. The dataset is automatically downloaded when you run the code.

## Usage

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Run the Jupyter notebooks for each GAN implementation:

   - `CNN_GAN.ipynb`: Standard GAN implementation.
   - `CNN_WGAN.ipynb`: Wasserstein GAN implementation.
   - `CNN_SNGAN.ipynb`: Spectral Normalization GAN implementation.
   - `MLP_GAN.ipynb`: Multi-Layer Perceptron GAN implementation.
   - `MLP_WGAN.ipynb`: Multi-Layer Perceptron Wasserstein GAN implementation.
   - `MLP_SNGAN.ipynb`: Multi-Layer Perceptron Spectral Normalization GAN implementation.

   You can run the notebooks using Jupyter:

   ```bash
   jupyter notebook
   ```

## Training

Each notebook contains a training loop that trains the respective GAN model for a specified number of epochs. The training process includes logging the generator and discriminator losses to a CSV file and saving generated images at various epochs.

## Results

After training, the generated images and loss plots can be found in the respective folders. The loss plots show the training progress of the generator and discriminator.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

### Instructions for Use
- Replace `<repository-url>` and `<repository-directory>` with the actual URL of your repository and the directory name.
- You can add more sections or modify existing ones based on your project requirements.
- Make sure to include any additional instructions or information that might be relevant to users of your project.