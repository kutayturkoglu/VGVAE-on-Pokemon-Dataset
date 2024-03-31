# Title

VQVAE Implementation for Pokemon Images Reconstruction
## Description

This project explores VQVAE at a beginner level, utilizing a VQVAE model adapted from Aaron van den Oord et al.'s paper and other resources. The Pokemon Image Dataset from Kaggle is used for training.

## Table of Contents

- [Description](#description)
- [Vector Quantized Variational Autoencoders (VQVAEs)](#vector-quantized-variational-autoencoders-vqvaes)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)

## Vector Quantized Variational Autoencoders (VQVAEs)

A VQVAE consists of three key components: Encoder, Decoder, and latent space. The encoder component, shrinks down the image size, and captures the most important features of the image in a smaller latent space. Unlike Variational Autoencoders, in VQVAEs, the latent space made out of discrete codewords.The discrete latent variables zare then calculated by a nearest neighbour look-up using the shared embedding space e.

![The formula for the nearest neighbour lookup]('data\nearestneighbour.png')

Afterwards, the codewords pass through the decoder part, which increases the dimension of the latent space to be able to reconstruct the images.

## Installation

- Clone the repository.
- Install dependencies from requirements.txt using pip:

## Usage

- Set up the environment and install dependencies.
- Run the training script to train the DCGAN model.
- Optionally, adjust hyperparameters and configurations as needed.

## Contributing

Contributions are welcome! Please reach me out for any possible contributions.

## License

This project is licensed under the MIT License.

## Credits

- Neural Discrete Representation Learning Aaron van den Oord et. al.
- Pokemon Dataset on Kaggle

