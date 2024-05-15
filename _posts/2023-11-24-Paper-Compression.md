---
layout: post
title:  awesome-compression
date:   2023-11-26 16:40:16
description: awesome-paper-compression
tags: paper
categories: sample-posts
---

# 2023-11-27

**【1】Understanding the Vulnerability of CLIP to Image Compression** [[NIPSworkshop](https://arxiv.org/abs/2311.14029)]

标题：了解 CLIP 易受图像压缩影响的原因

**【2】Perceptual Image Compression with Cooperative Cross-Modal Side Information**[[arxiv](https://arxiv.org/abs/2311.13847)]

标题：利用合作式跨模态侧信息进行感知图像压缩

**【3】Progressive Learning with Visual Prompt Tuning for Variable-Rate Image Compression**[[arxiv](https://arxiv.org/abs/2311.13846)]

标题：利用视觉提示调整进行渐进式学习，实现可变速率图像压缩

**【4】A Diffusion Model Based Quality Enhancement Method for HEVC Compressed Video** [[arxiv](https://arxiv.org/abs/2311.08746)]

标题：基于扩散模型的 HEVC 压缩视频质量增强方法

**【5】Blurry Video Compression: A Trade-off between Visual Enhancement and Data Compression**[[WACV2024](https://arxiv.org/abs/2311.04430)]

标题：模糊视频压缩： 视觉增强与数据压缩之间的权衡

**【6】Graph Based Cross-Channel Transform for Color Image Compression**[[ACMMM2023](https://dl.acm.org/doi/pdf/10.1145/3631710)]

标题：用于彩色图像压缩的基于图的跨通道变换

**【7】A Relay System for Semantic Image Transmission based on Shared Feature Extraction and Hyperprior Entropy Compression** [[arxiv](https://arxiv.org/abs/2311.10492)]

标题：基于共享特征提取和超熵压缩的语义图像传输中继系统

**【8】Advancing The Rate-Distortion-Computation Frontier For Neural Image Compression**[[ICIP2023](https://arxiv.org/abs/2311.12821)]

标题：推进神经图像压缩的速率-失真-计算边界

**【9】Corner-to-Center Long-range Context Model for Efficient Learned Image Compression** [[arxiv](https://arxiv.org/abs/2311.18103)]

标题：用于高效学习图像压缩的角到中心远距离上下文模型

# 2023-11-10
**【1】Toward Scalable Image Feature Compression: A Content-Adaptive and Diffusion-Based Approach** [[ACMMM2023](https://dl.acm.org/doi/pdf/10.1145/3581783.3611851)]

标题：可伸缩图像特征压缩

摘要：这篇论文提出了一种可扩展的图像特征压缩方法,该方法基于内容自适应和扩散模型,可以同时优化人类和机器视觉任务。传统的图像编解码器通常优先考虑信号保真度和人类感知,而忽略了机器视觉任务。基于深度学习的方法可以利用丰富的语义嵌入来实现良好的编解码性能,但这些紧凑的嵌入难以表示低级别的细节,如轮廓和纹理,导致重构不完美。此外,现有的基于学习的方法缺乏可扩展性。为了解决这些问题,本文提出了一种可扩展的图像压缩方法,该方法使用内容自适应扩散模型来准确地通过扩散过程编码纹理,同时增强人类感知并保留机器视觉任务的重要特征。该方法采用常用的特征提取器和图像生成器,以及马尔可夫调色板扩散模型来实现高效的数据压缩。通过利用协作纹理语义特征提取和伪标签生成,该方法可以准确地学习纹理信息。然后,应用内容自适应马尔可夫调色板扩散模型以可扩展的方式捕获低级别纹理和高级别语义知识。这个框架可以通过灵活选择中间扩散状态来实现优雅的压缩比控制,无需在不同的操作点上重新训练深度学习模型。实验证明,所提出的框架在图像重构和下游机器视觉任务(如对象检测、分割和面部关键点检测)方面比最先进的方法更有效。

**【2】Neural Video Compression with Spatio-Temporal Cross-Covariance Transformers** [[ACMMM2023](https://studios.disneyresearch.com/app/uploads/2023/09/Neural-Video-Compression-with-Spatio-Temporal-Cross-Covariance-Transformers-Paper.pdf)]

标题：时空交叉协方差变换器的神经视频压缩

摘要：这篇论文研究了神经视频压缩（NVC）方法，提出了一种名为Spatio-Temporal Cross-Covariance Transformer（ST-XCT）的新模块，以有效地同时利用时域和空域的冗余信息。ST-XCT模块将两个单独提取的特征融合为一个联合的空时特征，然后进行3D卷积操作和一个新颖的空时感知交叉协方差注意机制。这种设计允许在保持空时特征不变的情况下，建模全局跨通道之间的相关性，同时降低计算复杂度。基于ST-XCT，我们引入了一种新的基于变压器的端到端优化的NVC框架。ST-XCT模块被集成到NVC的各种关键编码组件中，如特征提取、帧重建和熵建模，证明了其泛化能力。大量实验表明，我们基于ST-XCT的NVC提案在各种标准视频基准数据集上实现了最先进的压缩性能。

**【3】DeepSVC: Deep Scalable Video Coding for Both Machine and Human Vision** [[ACMMM2023](https://dl.acm.org/doi/abs/10.1145/3581783.3612500), [code](https://github.com/LHB116/DeepSVC)]

标题：深度可伸缩视频编码

摘要：这篇论文提出了一种名为DeepSVC的深度可扩展视频编码器，旨在支持从机器到人类视觉的三层可扩展性。首先，设计了一个语义层，用于对捕获视频进行语义特征编码，以便于机器分析，并采用条件语义压缩（CSC）方法消除语义特征间的冗余。其次，设计了一个结构层，可以与语义层结合，以低质量预测捕获的视频。该层基于语义层使用IFP网络有效估计视频帧。第三，设计了一个纹理层，可以与上述两层结合以重构高质量视频信号，并利用IFP网络提高其编码效率。在大型IoVT系统中，DeepSVC可以按需提供语义层，而其他层则根据需求进行传输。实验结果表明，与流行的机器和人类视觉编解码器相比，所提出的DeepSVC具有更好的性能。与H.265/HEVC的可扩展扩展（SHVC）相比，所提出的DeepSVC在相同的mAP/PSNR/MS-SSIM下，平均比特每像素（bpp）降低了25.51%/27.63%/59.87%。

**【4】OpenFastVC: An Open Source Library for Video Coding Fast Algorithm Implementation** [[ACMMM2023](https://dl.acm.org/doi/pdf/10.1145/3581783.3613465), [code](https://openi.pcl.ac.cn/OpenCompression/OpenFastVC)]

标题：视频编码快速算法的开源库

**【5】Conditional Perceptual Quality Preserving Image Compression** [[CoRR23](https://cz5waila03cyo0tux1owpyofgoryroob.aminer.cn/71/5B/B6/715BB6435628C53F7F4F3C8BE434F80A.pdf)]

标题：条件感知质量保护的图像压缩

摘要：这篇论文提出了条件感知质量保持图像压缩的方法。作者通过在原始感知质量的基础上，加入用户定义的信息，扩展了感知质量的定义。

**【6】Dynamic Kernel-Based Adaptive Spatial Aggregation for Learned Image Compression** [[CoRR23](https://doi.org/10.48550/arXiv.2308.08723)]

标题：动态核自适应空间聚合的图像压缩

**【7】Non-Semantics Suppressed Mask Learning for Unsupervised Video Semantic Compression** [[ICCV23](https://openaccess.thecvf.com/content/ICCV2023/papers/Tian_Non-Semantics_Suppressed_Mask_Learning_for_Unsupervised_Video_Semantic_Compression_ICCV_2023_paper.pdf)]

标题：用于无监督视频语义压缩的非符号抑制掩码学习

**【8】TransTIC: Transferring Transformer-based Image Compression from Human Perception to Machine Perception** [[ICCV23](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_TransTIC_Transferring_Transformer-based_Image_Compression_from_Human_Perception_to_Machine_ICCV_2023_paper.pdf)]

标题：将基于变换器的图像压缩从人类感知转移到机器感知

**【9】Computationally-Efficient Neural Image Compression with Shallow Decoders** [[ICCV23](https://openaccess.thecvf.com/content/ICCV2023/papers/Yang_Computationally-Efficient_Neural_Image_Compression_with_Shallow_Decoders_ICCV_2023_paper.pdf), [code](https://github.com/mandt-lab/shallow-ntc)]

标题：利用浅层解码器实现计算高效的神经图像压缩

**【10】AdaNIC: Towards Practical Neural Image Compression via Dynamic Transform Routing** [[ICCV23](https://openaccess.thecvf.com/content/ICCV2023/papers/Tao_AdaNIC_Towards_Practical_Neural_Image_Compression_via_Dynamic_Transform_Routing_ICCV_2023_paper.pdf)]

标题：通过动态变换路由实现实用的神经图像压缩


# 2023-11-09
**【1】ICMH-Net: Neural Image Compression Towards both Machine Vision and Human Vision** [[ACMMM2023](https://dl.acm.org/doi/pdf/10.1145/3581783.3612041)]

标题： 面向机器视觉和人眼视觉的神经图像编码

摘要：本文介绍了一种设计分块、传输、重建和聚合图像隐特征表示的框架。 为实现人机视觉混合，PRTA设计了一个超参网络结构选择隐特征的子集用于机器视觉，未选择的部分用于人眼视觉的重建。
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/refimg/ICMH-Net.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

**【2】MLIC: Multi-Reference Entropy Model for Learned Image Compression**[[ACMMM2023](https://dl.acm.org/doi/pdf/10.1145/3581783.3611694)]

标题：可学习图像压缩的多参考帧熵模型

摘要：大多数熵模型仅能在一个维度获取信息相关性，然而隐特征表示通常包含通道相关性、局部空间相关性和全局空间相关性等。本文提出了以多参考的熵模型用于捕获隐特征表示的多种相关性。

**【3】NIF: A Fast Implicit Image Compression with Bottleneck Layers and Modulated Sinusoidal Activations** [[ACM2023](https://dl.acm.org/doi/pdf/10.1145/3581783.3613834) [code](https://github.com/aegroto/nif)]

标题：一个快速隐图像压缩框架

摘要：一个开源的INR图像编码器，超出了现有的SOTA，减少了隐神经网络的训练时间。

**【4】Learned Image Compression with Mixed Transformer-CNN Architectures**[[CVPR2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Liu_Learned_Image_Compression_With_Mixed_Transformer-CNN_Architectures_CVPR_2023_paper.pdf) [code](https://github.com/jmliu206/LIC_TCM)]

标题：混合Transformer-CNN架构的可学习图像压缩

摘要：本文提出一个transformer-cnn并行结构，复杂度可控。并且应用了一种参数有效的SwinTrans的通道熵编码结构。
<div class="row mt-3">
    <div class="row-sm mt-3 mt-md-0">
        {% include figure.html path="assets/refimg/Trans-CNN.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
    <div class="row-sm mt-3 mt-md-0">
        {% include figure.html path="assets/refimg/Trans-CNN2.png" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>

**【5】Frequency Disentangled Features in Neural Image Compression** [[ICIP2023](https://arxiv.org/abs/2308.02620)]

标题：神经图像压缩中的频率解藕特征

摘要：神经图像压缩的设计性能提升主要来源于熵模型如何能很好匹配隐向量的真实分布。本文提出了一种特征层频率解藕的方法实现松弛的标量量化，以达到高熵特征以更低码率表示。
<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/refimg/frequencydis.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>
</div>