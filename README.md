# Generative Adversarial Networks

This repository presents the **basic notions** that involve the concept of Generative Adversarial Networks.

## Models

Definition and training some models, such as:

* [GAN with MNIST](https://github.com/mafda/generative_adversarial_networks_101/blob/master/src/01_GAN_MNIST.ipynb)
* [DCGAN with MNIST](https://github.com/mafda/generative_adversarial_networks_101/blob/master/src/02_DCGAN_MNIST.ipynb)
* [CGAN with MNIST](https://github.com/mafda/generative_adversarial_networks_101/blob/master/src/03_CGAN_MNIST.ipynb)
* [CCGAN with MNIST](https://github.com/mafda/generative_adversarial_networks_101/blob/master/src/04_CCGAN_MNIST.ipynb)

## Results

Training models with Keras and TensorFlow

### Generative Adversarial Networks - GANs
A GANs implementation using fully connected layers.

| Epoch 00 | Epoch 100 | Loss |
|----------|-----------|------|
| ![GAN with MNIST](img/00_gan.png) | ![GAN with MNIST](img/100_gan.png)| ![GAN with MNIST](img/loss_gan.png)|

### Deep Convolutional Generative Adversarial Networks - DCGANs
A DCGANs implementation using the transposed convolution technique.

| Epoch 00 | Epoch 100 | Loss |
|----------|-----------|------|
| ![GAN with MNIST](img/00_dcgan.png) | ![GAN with MNIST](img/100_dcgan.png)| ![GAN with MNIST](img/loss_dcgan.png)|

### Conditional Generative Adversarial Nets - CGANs
A CGANs implementation using fully connected layers and embedding layers.

| Epoch 00 | Epoch 100 | Loss |
|----------|-----------|------|
| ![CGAN with MNIST](img/00_cgan.png) | ![CGAN with MNIST](img/100_cgan.png)| ![CGAN with MNIST](img/loss_cgan.png)|

### Context-Conditional Generative Adversarial Networks - CCGANs
A CCGANs implementation using U-Net and convolutional neural network.

| Epoch 00 | Epoch 100 | Loss |
|----------|-----------|------|
| ![CGAN with MNIST](img/00_ccgan.png) | ![CGAN with MNIST](img/100_ccgan.png)| ![CGAN with MNIST](img/loss_ccgan.png)|

