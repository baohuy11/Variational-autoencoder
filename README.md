<h1 align="center">
  <b>PyTorch VAE</b><br>
</h1>

<p align="center">
      <a href="https://www.python.org/">
        <img src="https://img.shields.io/badge/Python-3.5-ff69b4.svg" /></a>
       <a href= "https://pytorch.org/">
        <img src="https://img.shields.io/badge/PyTorch-1.3-2BAF2B.svg" /></a>
       <a href= "https://github.com/AntixK/PyTorch-VAE/blob/master/LICENSE.md">
        <img src="https://img.shields.io/badge/license-Apache2.0-blue.svg" /></a>
         <a href= "https://twitter.com/intent/tweet?text=PyTorch-VAE:%20Collection%20of%20VAE%20models%20in%20PyTorch.&url=https://github.com/AntixK/PyTorch-VAE">
        <img src="https://img.shields.io/twitter/url/https/shields.io.svg?style=social" /></a>

</p>

A simple tutorial of Variational AutoEncoder(VAE) models. This repository contains the implementations of following VAE families.


* [Variational AutoEncoder](https://arxiv.org/pdf/1312.6114.pdf) (VAE, D.P. Kingma et. al., 2013)
* [Vector Quantized Variational AutoEncoder](https://arxiv.org/pdf/1711.00937.pdf) (VQ-VAE, A. Oord et. al., 2017)

# Requirements
```bash
pip install -r requirements.txt
```

# How-to-use
simply run the <file_name>.ipynb files using jupyter notebook.

# Experimental Results
## Variational AutoEncoder (VAE)
- Trained on MNIST dataset for 10 epochs

- Origin data

![MNIST_origin](./assets/mnist_origin.png) 

- Reconstructed data

![VAE_reconstructed](./assets/mnist_reconstruct.png)

- Generated random samples from noise vector

![VAE_generated_sample](./assets/mnist_generate.png)

- MNIST latent space

![MNIST_latent_space](./assets/mnist_latent_space.png)

## Vector Quantized Variational AutoEncoder (VQ-VAE)
- Trained on CIFAR-10 dataset for 10 epochs

- Origin data

![CIFAR-10_origin](./assets/cifar-10_origin.png) 

- Reconstructed data

![CIFAR-10_reconstructed](./assets/cifar-10_reconstruct.png)

- Generated random samples from noise vector

![CIFAR-10_generated_sample](./assets/cifar-10_generate.png)

