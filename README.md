# Image_Colorization_VAE
Image colorization using Variational Autoencoders (VAE). Converts grayscale images to color by learning color distributions from datasets. Encodes grayscale inputs into a latent space and decodes into full-color images.
Image Colorization using Variational Autoencoders (VAE)

This repository contains an implementation of an image colorization model using Variational Autoencoders (VAE). The goal of this project is to automatically colorize grayscale images by learning the underlying color distribution from a dataset of colored images. The VAE architecture is used to encode the grayscale input into a latent space and decode it into a full-color image.

Key Features:
VAE-based Architecture: Leverages the power of Variational Autoencoders to learn a probabilistic latent space for image colorization.

Grayscale to Color Transformation: Converts single-channel grayscale images into three-channel RGB images.

Customizable Training: Supports training on custom datasets and allows tuning of hyperparameters like latent space dimensions, learning rate, and batch size.

Pre-trained Models: Includes pre-trained models for quick inference and demonstration.

Evaluation Metrics: Provides metrics such as PSNR (Peak Signal-to-Noise Ratio) and SSIM (Structural Similarity Index) to evaluate the quality of colorized images.

Dataset: https://drive.google.com/drive/folders/1KeJbfUykGnPlz0q08_b1IjtW8OxkPdQ9?usp=sharing
