# GAN for Cats Image Generation

## Purpose
Create a Generative Adversarial Network (GAN) to generate realistic cat images using a [Cats faces 64x64 dataset](https://www.kaggle.com/datasets/spandan2/cats-faces-64x64-for-generative-models/data).

## Overview
- **Generator**: Converts random noise to 64x64x3 images using transposed convolutions.
- **Discriminator**: Identifies real vs. generated images using standard convolutions.
- **Training**: Optimized with Adam; generator and discriminator losses calculated via adversarial training.

## Training Visualization
![Training Progress](generated_cats/cats_gan.gif)

