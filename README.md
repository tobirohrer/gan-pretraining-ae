# GAN pretraining for Autoencoders

This repository contains the code for the paper [GAN pretraining for deep convolutional
autoencoders applied to Software-based Fingerprint
Presentation Attack Detection](https://arxiv.org/pdf/2105.10213.pdf). 

**In short:** A Wasserstein GAN is used to pretrain a Autoencoder which is used for classification. The project is devided into two jupyter notebooks. One contains the code for the Wasserstein GAN. The other contains the Code for the autoencoder, which uses the pretrained and stored weights from the GAN. 

## Installation
The code was developed using python version 3.7 and using the dependencies in the `requirements.txt` file.
