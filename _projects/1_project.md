---
layout: page
title: Temporal Consistency Learning of Inter-Frames for Video Super-Resolution
description: 
img: assets/img/TCNet.jpg
importance: 1
category: Publication
---
*Meiqin Liu<sup>1</sup>, Shuo Jin<sup>1</sup>, [Chao Yao](https://yaochao1986.github.io/)<sup>2</sup>, Chunyu Lin<sup>1</sup>, Yao Zhao<sup>1</sup>*

<sup>1</sup> Beijing Jiaotong University, Beijing, China

<sup>2</sup> University of Science and Technology Beijng, Beijing, China

## Abstract
Video super-resolution (VSR) is a task that aims to reconstruct high-resolution (HR) frames from the low-resolution (LR) reference frame and multiple neighboring frames. The vital operation is to utilize the relative misaligned frames for the current frame reconstruction and preserve the consistency of the results. Existing methods generally explore information propagation and frame alignment to improve the performance of VSR. However, few studies focus on the temporal consistency of inter-frames. In this paper, we propose a Temporal Consistency learning Network (TCNet) for VSR in an end-toend manner, to enhance the consistency of the reconstructed videos. A spatio-temporal stability module is designed to learn the self-alignment from inter-frames. Especially, the correlative matching is employed to exploit the spatial dependency from each frame to maintain structural stability. Moreover, a self-attention mechanism is utilized to learn the temporal correspondence to implement an adaptive warping operation for temporal consistency among multi-frames. Besides, a hybrid recurrent architecture is designed to leverage short-term and long-term information. We further present a progressive fusion module to perform a multistage fusion of spatio-temporal features. And the final reconstructed frames are refined by these fused features. Objective and subjective results of various experiments demonstrate that TCNet has superior performance on different benchmark datasets, compared to several state-of-the-art methods.

## Pipeline
<div class="row" align=center>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/TCNet.jpg" title="TCNet" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
     Overview of the proposed TCNet, which is mainly made up with information pre-popagation, spatio-temporal stability module, progressive fusion, and refinement.
</div>

## Highlights
1. We introduce a temporal consistency learning strategy that is designed for the alignment of temporal information from inter-frames. The global motion tendency is learned across multiple frames to enhance the spatio-temporal stability.

2. We redesign a hybrid recurrent architecture for information propagation. It jointly takes advantages of slidingwindow and recurrent network, which is able to exploit the short-term and long-term information.

3. We adopt a progressive fusion module based on pyramid structure for efficiently aggregating the consistent features. The final restored frames are refined with these fused features.

## Results
<div class="row" align=center>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/TCNetTable.jpg" title="TCNetTable" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row" align=center>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/TCNetPic.jpg" title="TCNetPic" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Materials


[paper](https://yaochao1986.github.io/assets/pdf/TCSVT-Temporal%20Consistency%20Learning%20of%20Inter-Frames%20for%20Video%20Super-Resolution.pdf) 
[Code](https://github.com/Kimsure/TCNet-for-VSR)

## Citation
{% raw %}

```
@article{liu2022temporal,
  title={Temporal Consistency Learning of Inter-Frames for Video Super-Resolution},
  author={Liu, Meiqin and Jin, Shuo and Yao, Chao and Lin, Chunyu and Zhao, Yao},
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  volume={33},
  number={4},
  pages={1507--1520},
  year={2022},
  publisher={IEEE}
}
```

{% endraw %}
## Contact

If you have any questions, please contact Chao Yao at yaochao@ustb.edu.cn
