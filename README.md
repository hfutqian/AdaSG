# Rethinking Data-Free Quantization as a Zero-Sum Game [AAAI 2023]
This repository is the official code for the paper "Rethinking Data-Free Quantization as a Zero-Sum Game" by Biao Qian, Yang Wang (corresponding author: yangwang@hfut.edu.cn), Richang Hong, Meng Wang (AAAI 2023, Washington, USA).


## Requirements
* python3.6
* pytorch1.3.1
* cuda10.0
* lmdb

## Usages

To quantize the pre-trained ResNet-20 on CIFAR-100, run the following command:
```
python main.py --conf_path=./cifar100_resnet20.hocon --id=01
```

To quantize the pre-trained ResNet-18 on ImageNet, run the following command:
```
python main.py --conf_path=./imagenet_res18.hocon --id=01
```
