# survey/overview/review

- Blind Deblurring综述。
  - [Blind Deblurring using Deep Learning: A Survey](https://arxiv.org/pdf/1907.10128.pdf)[2019.07]

- Image inpainting综述

  - [2019.09][Image inpainting: A review](https://arxiv.org/pdf/1909.06399.pdf)
  
- 图像去除雨滴算法综述
  - [2019.09][A Survey on Rain Removal from Video and Single Image](https://arxiv.org/pdf/1909.08326.pdf)

- 图像去噪综述。
  - [2019][Deep Learning on Image Denoising: An overview](https://arxiv.org/pdf/1912.13171.pdf)
  
## Super-Resolution

- CVPR2019论文，中科大，自动化所，旷视等联合提出Meta-SR, 单一模型解决任意尺度的 super-resolution。模型包括：Feature Learning Module和MetaUpscale Module。Feature Learning Module
可使用RDN，EDSR，通用的特征提取模块(类似ResNet/DenseNet)；Meta-Upscale学习不同比率下上采样权重。可使用的损失函数包括L1,L2正则化。Super-Resolution是否可以理解为如何语义分割的上采样过程？super-resolution的backbone，upsample,loss函数都可借鉴分类/分割的设计，遍地都是机会啊。
  - [Meta-SR: A Magnification-Arbitrary Network for Super-Resolution](https://arxiv.org/pdf/1903.00875.pdf)
  
## Underexposed Photo Enhancement
  
- CVPR2019论文，香港中文大学等提出。论文假设自然图像的光照图有着相对简单的先验，让网络模型去学习image-to-illumination mapping，实现retinex的图像增强。另外论文提出损失函数是Reconstruction Loss(L2)+Smoothness Loss+Color Loss。论文在MIT-Adobe FiveK( 5,000 raw images)之外标注3,000训练集训练模型(什么样的模型用这么少的训练集？)backbone使用VGG16,Titan X Pascal GPU训练40 epochs。
  - [Underexposed Photo Enhancement using Deep Illumination Estimation](http://jiaya.me/papers/photoenhance_cvpr19.pdf)
  
## Obstructions

- 台湾大学，谷歌提出，图像去除遮挡算法。
  - [Learning to See Through Obstructions](https://arxiv.org/pdf/2004.01180.pdf)
  - <https://github.com/alex04072000/ObstructionRemoval>

## Evaluation Metrics

PSNR and SSIM

## dataset

MIT-Adobe FiveK

