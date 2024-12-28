# GAN Learning Repository

## Models
This repository contains modified implementations of various GANs (Generative Adversarial Networks) including:
1. Vanilla GAN
2. Conditional GAN (CGAN)
3. Deep Convolutional GAN (DCGAN)
4. Wasserstein GAN (WGAN)
5. Wasserstein GAN with Gradient Penalty (WGANGP)

## Datasets
1. [MNIST Dataset](https://pytorch.org/vision/main/generated/torchvision.datasets.MNIST.html)
2. [Anime Face Dataset](https://www.kaggle.com/datasets/splcher/animefacedataset)
3. [Celeba Dataset](https://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)

## Environment
Install and activate the conda environment with the following commands:
```bash
conda env create -f environment.yml
conda activate GANs
```

## Citations
```
@inproceedings{liu2015faceattributes,
    title = {Deep Learning Face Attributes in the Wild},
    author = {Liu, Ziwei and Luo, Ping and Wang, Xiaogang and Tang, Xiaoou},
    booktitle = {Proceedings of International Conference on Computer Vision (ICCV)},
    month = {December},
    year = {2015}
}
```
