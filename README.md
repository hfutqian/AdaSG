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

## Citation
```
@article{Qian_Wang_Hong_Wang_2023,
  title={Rethinking Data-Free Quantization as a Zero-Sum Game},
  volume={37},
  url={https://ojs.aaai.org/index.php/AAAI/article/view/26136},
  DOI={10.1609/aaai.v37i8.26136},
  number={8},
  journal={Proceedings of the AAAI Conference on Artificial Intelligence},
  author={Qian, Biao and Wang, Yang and Hong, Richang and Wang, Meng},
  year={2023},
  month={Jun.},
  pages={9489-9497}
}
```
