# SODA: Bottleneck Diffusion Models for Representation Learning 

* Elena Bianchini
* Alessandro Ferrante

This project aims to implement a simplified version of the self-supervised diffusion model SODA, presented in the following [paper](https://arxiv.org/pdf/2311.17901.pdf).
The model is designed for representation learning. It is made by an encoder, whose purpose is to create a compact representation of a view, which guides the denoising process of a decoder.
More details are presented into the notebook `code.ipynb`.

## Instructions
To use the code, it is necessary to clone the repository and to install all the missing packets, through a command line such as the following example: `pip install torch`. 

Then, it's possible to try it by opening the notebook `code.ipynb` and running all the cells in a sequential way. We suggest you to load the pretrained checkpoints and do not train the model again. :smile:  
