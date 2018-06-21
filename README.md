# Generative Adversarial Networks

This repository presents the **basic notions** that involve the concept of Generative Adversarial Networks.

## Models

Definition and training some models, such as:

* [GAN with MNIST](https://github.com/mafda/generative_adversarial_networks_101/blob/master/src/01_GAN_MNIST.ipynb)
* [DCGAN with MNIST](https://github.com/mafda/generative_adversarial_networks_101/blob/master/src/02_DCGAN_MNIST.ipynb)

## Results

### Training GANs with Keras and TensorFlow
A standard GANs implementations using fully connected layers and the [Keras](https://keras.io/) library.

* Generated MNIST images at epoch 10.
![GAN with MNIST](img/00_gan.png)

* Generated MNIST images at epoch 90.
![GAN with MNIST](img/100_gan.png)

* Loss at every epoch for 100 epochs.
![GAN with MNIST](img/loss_gan.png)

### Training DCGANs with Keras and TensorFlow
A DCGANs implementation using the transposed convolution technique and the [Keras](https://keras.io/) library.

* Generated MNIST images at epoch 10.
![GAN with MNIST](img/00_dcgan.png)

* Generated MNIST images at epoch 90.
![GAN with MNIST](img/100_dcgan.png)

* Loss at every epoch for 100 epochs.
![GAN with MNIST](img/loss_dcgan.png)
