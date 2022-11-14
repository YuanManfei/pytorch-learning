# install

## Create virtual environment
```
conda create -n env_torch
```
check environment list
```
conda env list
```
![plot](https://github.com/YuanManfei/pytorch-learning/blob/main/install/img/check_list.png)

In the environment list, we can see env_torch is successfully created.

## CUDA and cuDNN install
https://medium.com/geekculture/install-cuda-and-cudnn-on-windows-linux-52d1501a8805  

## Install pytorch

active virtual environment env_torch and install pytorch
```
conda activate env_torch
```
Go to https://pytorch.org/get-started/locally/  
Select your preferences and run the install command.
![plot](https://github.com/YuanManfei/pytorch-learning/blob/main/install/img/install.png)
```
conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia
```
