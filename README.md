# Benchmarking Neural Network Robustness to Common Corruptions and Perturbations

This repository contains the datasets and some code for the paper [Benchmarking Neural Network Robustness to Common Corruptions and Perturbations](https://arxiv.org/abs/1807.01697) (ICLR 2019) by Dan Hendrycks and Tom Dietterich.

Requires Python 3+ and PyTorch 0.3+.

## ImageNet-C

<img align="center" src="assets/imagenet-c.png" width="750">

[Download Tiny ImageNet-C here.](https://berkeley.box.com/s/6zt1qzwm34hgdzcvi45svsb10zspop8a) [(Mirror.)](https://zenodo.org/record/2469796)

[Download ImageNet-C here.](https://drive.google.com/drive/folders/1HDVw6CmX3HiG0ODFtI75iIfBDxSiSz2K?usp=sharing) [(Mirror.)](https://zenodo.org/record/2235448)

Tiny ImageNet-C has 200 classes with images of size 64x64, while ImageNet-C has all 1000 classes where each image is the standard size. For even quicker experimentation, there is [CIFAR-10-C](https://zenodo.org/record/2535967), but improvements on CIFAR-10-C may be much less indicative of ImageNet-C improvements.

## ImageNet-P

<img align="center" src="assets/translate.gif" width="224"> <img align="center" src="assets/tilt.gif" width="224"> <img align="center" src="assets/spatter.gif" width="224">

<sub><sup>ImageNet-P sequences are MP4s not GIFs. The spatter perturbation sequence is a validation sequence.</sup></sub>

[Download Tiny ImageNet-P here.](https://berkeley.box.com/s/19m2ppji0xsqgtkrs95329bqftbvncx9) [(Mirror.)](https://zenodo.org/record/2469796)

[Download ImageNet-P here.](https://drive.google.com/drive/folders/1vRrDaWA6-_GaUZqOmovWrr4W34aiSLu7?usp=sharing)


## Citation

If you find this useful in your research, please consider citing:

    @article{hendrycks2019robustness,
      title={Benchmarking Neural Network Robustness to Common Corruptions and Perturbations},
      author={Dan Hendrycks and Thomas Dietterich},
      journal={Proceedings of the International Conference on Learning Representations},
      year={2019}
    }

Part of the code was contributed by [Tom Brown](https://github.com/nottombrown).

## Icons-50 (From an Older Draft)

<img align="center" src="assets/icons-50.png" width="750">

Download Icons-50 [here](https://berkeley.box.com/s/jcem6ik7rxr6594lg99kmrdo01ue6yjt) or [here.](https://drive.google.com/drive/folders/16_kaFo3uUoS-U8FTDm4nUh6Vo21UVnJX?usp=sharing)

