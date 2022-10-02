# Faces-DCGAN-SAGAN

The aim of this project is to learn and implement generative models based on
differentiable generator networks, mainly Deep Convolutional GAN (DCGAN)
and Self-Attention GAN (SA-GAN). Project requirements include:<br>
<ul>
<li>Implementation of Deep Convolutional GAN and Self-Attention GAN consisting of a Generator (G) and Discriminator (D) using the CIFAR10 dataset.
<li>Applying Spectral Normalization (SN) on G and D.

<li>Implementation of self-attention (SA) GAN module

<li>Implementation of Wasserstein Loss function for the training

<li>Applying Frechet Inception Distance (FID) as an evaluation metric and validating the training epochs using FID with a validation set.

<li>Computing the FID score during training at every 500 iterations and visualising the attention layers

</ul>

##  Deep Convolutional GAN
Architecture guidelines for stable Deep Convolutional GANs:

<ul>
<li> Replace any pooling layers with strided convolutions (discriminator) and fractional-strided convolutions (generator).

<li>Use batchnorm in both the generator and the discriminator


<li>Remove fully connected hidden layers for deeper architectures.


<li>Implementation of Wasserstein Loss function for the training

<li>Use ReLU activation in generator for all layers except for the output, which uses Tanh

<li>Use LeakyReLU activation in the discriminator for all layers.

</ul>




