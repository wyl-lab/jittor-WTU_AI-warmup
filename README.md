# jittor-纺大人工智能小队-热身赛
jittor-warmup_match

| 第三届计图挑战赛开源文档

热身赛题介绍
本赛道将在数字图片数据集 MNIST 上训练 Conditional GAN（Conditional generative adversarial nets）模型，通过输入一个随机向量 z 和额外的辅助信息 y (如类别标签)，生成特定数字的图像。

## 简介
| 简单介绍项目背景、项目特点

本项目包含了第三届计图挑战赛计图 - 草图生成风景比赛的代码实现。
本项目的特点是：采用了 XX 方法对 YY 处理，取得了 ZZ 的效果。

## 安装 
| 介绍基本的硬件需求、运行环境、依赖安装方法

本项目可在 1 张 GPU :

	NVIDIA GeForce RTX 2080 Ti

	驱动程序版本:	31.0.15.3623
	驱动程序日期:	2023/6/8
	DirectX 版本:	12 (FL 12.1)
	物理位置：	PCI 总线 1、设备 0、功能 0

	利用率	1%
	专用 GPU 内存	1.7/11.0 GB
	共享 GPU 内存	0.1/32.0 GB
	GPU 内存	1.8/43.0 GB ,

运行训练时间约为 8 小时。

#### 运行环境
- ubuntu 20.04 LTS
- python >= 3.7
- jittor >= 1.3.0

#### 安装依赖
执行以下命令安装 python 依赖
```
pip install -r requirements.txt
```

## 训练
｜ 介绍模型训练的方法

python CGAN.py

## 致谢
| 对参考的论文、开源库予以致谢，可选

此项目基于论文 *A Style-Based Generator Architecture for Generative Adversarial Networks* 实现，部分代码参考了 [jittor-gan](https://github.com/Jittor/gan-jittor)。

## 注意事项

点击项目的“设置”，在Description一栏中添加项目描述，需要包含“jittor”字样。同时在Topics中需要添加jittor。

![image-20220419164035639](https://s3.bmp.ovh/imgs/2022/04/19/6a3aa627eab5f159.png)
