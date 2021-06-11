# Final Thesis
Class-incremental learning for image recognition

## Description
Repository for my final thesis. <br/>
FER, AY 2020/2021

### Method description
For my final thesis I implemented deep model consolidation. This method uses double distillation loss to consolidate two neural networks. Double distillation loss is a method based on a popular technique called knowledge distillation. Method is described in more detail in the [original paper](https://arxiv.org/abs/1903.07864).

## Usage
For running the code you should follow these steps:
1. Download CIFAR-100 and ImageNet32 test set in the proper folders in the provided folder structure.
2. Run data_prep.ipynb
3. Choose the configuration you wish to run in the configuration_setup.txt and copy the provided parameters in the proper code cell in DMC.ipynb
4. Run DMC.ipynb
5. Upon completion run Graphing_solutions.ipynb

Note 1. If you wish to test some other depth of residual network the code is provided to do that on the entire CIFAR-100 dataset. Just change the resnet_type parameter and run Resnet32.ipynb
Note 2. Every jupyter notebook provided is meant to be run on Google Colab platform.


## Mentor
* Prof. dr. sc. Siniša Šegvić
