# CUSTOM_pix2pixHD
# NOVEL HEAD VIEW SYNTHESIS WITH PIX2PIXHD GAN MODEL

Given a source image and a target image, it can synthesize a head image from the source with pose from the target image


## Prerequisites
- Linux or macOS
- Python 2 or 3
- NVIDIA GPU (11G memory or larger) + CUDA cuDNN

## Getting Started
### Installation
- Install PyTorch and dependencies from http://pytorch.org
- Install python libraries [dominate](https://github.com/Knio/dominate).
```bash
pip install dominate
```
- Clone this repo:
```bash
git clone https://github.com/vedant-916/CUSTOM_pix2pixHD.git
cd pix2pixHD
```
Use train.py to train on your own dataset
Use test.py to test your trained model

Example Result

<p align='center'>  
  <img src='https://github.com/vedant-916/CUSTOM_pix2pixHD/blob/main/SRC.png' width='250'/>
  <img src='https://github.com/vedant-916/CUSTOM_pix2pixHD/blob/main/TARGET.png' width='250'/>
  <img src='https://github.com/vedant-916/TEST/blob/main/CUSTOM_pix2pixHD/SYNTHESIZED.png' width='250'/>
</p>

<p align="center">
  SOURCE IMAGE  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      TARGET IMAGE   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;        SYNTHESIZED IMAGE
</p>

This project is inspired by https://github.com/NVIDIA/pix2pixHD



