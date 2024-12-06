---
layout: page
title: 计算机系统基础课程
description: 
img: assets/img/computer%system.jpg
importance: 2
category: Course
---
### 课程概述与简介：

本课程主要面向研究生，共32学时，讲述深度学习基本概念、经典深度学习模型以及最新的深度学习网络技术。本课程包括理论学习和实践应用两方面，除课堂讲授外，学生还需要通过实践和前沿论文阅读以熟练掌握深度学习平台、工具和前沿技术。

### 课程学习导引：
课程主要教学内容：
* 第1讲-绪论。本讲主要介绍人工智能、机器学习、神经网络、深度学习等研究内容和发展。
* 第2讲-基础知识。本讲主要介绍机器学习和深度学习的基本概念、数学基础和常见的线性模型。
* 第3讲-深度学习工具。本讲主要介绍常用的深度学习开源框架、核心组建、主流框架和Pytorch基础。
* 第4讲-前馈神经网络。本讲主要介绍人工神经网络的基本原理、神经网络基础结构、反向传播算法、自动梯度计算、神经网络参数优化方法等。
* 第5讲-深度模型优化与正则化。本讲主要介绍网络优化概念、小排量梯度下降、学习率及梯度优化、参数初始化与数据预处理、逐层归一化、超参数优化、过拟合与正则化等。
* 第6讲-卷积神经网络。本讲主要介绍卷积运算基础，卷积网络的基本组件以及典型的卷积方式和神经网络架构。
* 第7讲-循环神经网络。本讲主要介绍循环神经网络结构、BPTT、LSTM、GRU等。
* 第8讲-深度学习前沿与局限。本讲主要介绍深度学习前沿发展，包括Transformer等新型深度神经网络技术等基本原理等。

推荐教材和课程包括：
* Dive into Deep Learning [English](https://d2l.ai) [中文版](https://zh.d2l.ai/) [视频](https://space.bilibili.com/1567748478/channel/seriesdetail?sid=358497)
* 深度学习（花书）[English](https://www.deeplearningbook.org/)
* Deep Learning with Pytorch [English](https://isip.piconepress.com/courses/temple/ece_4822/resources/books/Deep-Learning-with-PyTorch.pdf)
* 斯坦福CS231n: Deep Learning for Computer Vision [课程主页](http://cs231n.stanford.edu/) [视频](https://www.bilibili.com/video/BV1nJ411z7fe/?spm_id_from=333.337.search-card.all.click&vd_source=945cf64d12eb8c35f4af718b31e3374d)
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/d2l.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/DeepLearning.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/dlp.jpeg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/CS231N.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

#### 如何阅读 *Dive into Deep Learning*?
对于初学者，建议重点阅读其中的第1，2，3，4，5，6，7，10，13章，并且尽可能地利用pytorch实现书中提供的代码。

#### 如何学习 *CS231n*?
CS231n是由计算机视觉领域第一个大规模视觉数据集ImageNet的发起者Feifei Li教授开设的著名深度学习课程。在本课程中，大家可以了解计算机视觉的多个基础领域，包括图像分类、定位和检测等。本课程深入探讨了深度学习架构的细节，重点是学习深度学习模型在各个任务中的应用，特别是图像分类。通过课程学习，学生可以掌握如何实现和训练自己的神经网络，并详细了解计算机视觉领域的前沿研究。

学生可以通过上面的链接获取课程的视频链接和相关课程资料。建议按照课程安排依次学习了解相关课程内容，并在课后动手实践。

### 经典文章推荐
1. Basic Network

    * [AlexNet] Imagenet classification with deep convolutional neural networks [NeurIPS link](https://proceedings.neurips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)
    * [ResNet] Deep Residual Learning for Image Recognition [Arxiv](https://arxiv.org/abs/1512.03385)
    * [Transformer] Attention Is All You Need [Arxiv](http://arxiv.org/abs/1706.03762)
    * [ViT] An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale [Arxiv](http://arxiv.org/abs/2010.11929)
    * [Swin] Swin Transformer: Hierarchical Vision Transformer using Shifted Windows [Arxiv](http://arxiv.org/abs/2103.14030)
2. Object Detection
    * [Fast R-CNN] Fast R-CNN [Arxiv](https://arxiv.org/abs/1504.08083)
    * [Faster R-CNN] Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks[Arxiv](https://arxiv.org/abs/1506.01497)
    * [YOLO] You Only Look Once: Unified, Real-Time Object Detection [Arxiv](https://arxiv.org/abs/1506.02640)
    * [FCOS] FCOS: Fully Convolutional One-Stage Object Detection [Arxiv](https://arxiv.org/abs/1904.01355)
    * [DETR] End-to-End Object Detection with Transformers [Arxiv](https://arxiv.org/abs/2005.12872)
3. Image Segmentation
    * [FCN] Fully Convolutional Networks for Semantic Segmentation [Arxiv](https://arxiv.org/abs/1411.4038)
    * [U-Net] U-Net: Convolutional Networks for Biomedical Image Segmentation [Arxiv](https://arxiv.org/abs/1505.04597)
    * [DeepLab] DeepLab: Semantic Image Segmentation with Deep Convolutional Nets, Atrous Convolution, and Fully Connected CRFs [Arxiv](https://arxiv.org/abs/1606.00915)
    * [PSPNet] Pyramid Scene Parsing Network [Arxiv](http://arxiv.org/abs/1612.01105)
    * [Mask R-CNN] Mask R-CNN [Arxiv](https://arxiv.org/abs/1703.06870)
    * [Non-local] Non-local Neural Networks [Arxiv](http://arxiv.org/abs/1711.07971)
    * [CCNet] CCNet: Criss-Cross Attention for Semantic Segmentation [Arxiv](http://arxiv.org/abs/1811.11721)

### 其它教学参考资料
* 《深度学习(PyTorch)》课程视频及ppt，纽约大学 Yann Lecun [链接](https://cds.nyu.edu/deep-learning/)
* 旷世&北大《深度学习实践》[链接](https://www.bilibili.com/video/BV1E7411t7ay/?spm_id_from=333.1007.top_right_bar_window_history.content.click&vd_source=945cf64d12eb8c35f4af718b31e3374d)
* 日内瓦大学《深度学习》课程 [链接](https://fleuret.org/dlc/?continueFlag=94beb9def3b2abc69ded207e71ffda33)
* Deep Learning学习笔记 [链接](https://blog.csdn.net/zouxy09/category_1387932.html)
* 深度学习博客 [链接](https://blog.csdn.net/hjimce/category_3163421.html)
* 深度学习资源汇总 [链接](https://zhuanlan.zhihu.com/p/27180274)