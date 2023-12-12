# Autoencoder-based Models for Breast Cancer Detection

This repository explores the use of autoencoders for breast cancer detection using ultrasound image data.

## Data

The data used in this study is the Breast Ultrasound Images dataset from Kaggle: [Link to dataset on Kaggle](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset/).

## Autoencoder Models

Three different autoencoder models are implemented:

1. **Linear Autoencoder:** A basic autoencoder with linear activation functions.

   ![Linear Autoencoder Architecture](./linear_autoencoder.png)

2. **Convolutional Autoencoder (CNN Autoencoder):** A convolutional autoencoder that utilizes convolutional and pooling layers to extract features from the image data.

   ![CNN Autoencoder Architecture](./convolutional_autoencoder.png)

3. **Variational Autoencoder (VAE):** A generative autoencoder that learns a latent representation of the data while minimizing reconstruction error and maximizing data reconstruction probability.

   ![Variational Autoencoder (VAE) Architecture](./vae.png)

**Feel free to use the notebook and contribute to the project!**

I encourage you to explore the code, make modifications, and share your findings.
