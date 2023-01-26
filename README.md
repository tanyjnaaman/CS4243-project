# CS4243 project: Image Inpainting on a Frogs dataset

## Context

This repo contains the code for my CS4243 project on image inpainting.

At a high level, we scrape 200k images from [iNaturalist](https://www.inaturalist.org/), create a dataset using `torch.data.Dataset`, and then train several GAN models on it. 

In particular, we explore: 
* [Partial]() and [Gated]() convolutions
* [Multitask]() architectures
* [Contrastive]() formulations of the task
* [Discrimination at different scales]() - specifically, local vs. global scale discrimination
* [PixelShuffle]() and similar upsampling techniques
* [Geometric learning via GIN convolutions]() by formulating the image task as a graph task

You can find most of them in the `active_experiments` folder, though it's not complete.

We also explored the use of [diffusion models](), but did not have the time or bandwidth to.

## Outcomes
For a neater presentation of the material, check out our [video](). 

The project was awarded an A+ and the top project for the class. See the [digital certificate]().

## Note
The repo is slightly messy. Will clean it up when I find some time to. 
