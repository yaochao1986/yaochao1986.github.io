---
layout: page
title: JNMR Joint Non-Linear Motion Regression for Video Frame Interpolation
description: 
img: assets/img/JNMRchat.jpg
importance: 1
category: Publication
---
*Meiqin Liu<sup>1</sup>, Chenming Xu<sup>1</sup>, [Chao Yao](https://yaochao1986.github.io/)<sup>2</sup>, Chunyu Lin<sup>1</sup>, Yao Zhao<sup>1</sup>*

<sup>1</sup> Beijing Jiaotong University, Beijing, China

<sup>2</sup> University of Science and Technology Beijng, Beijing, China

## Abstract
Video frame interpolation (VFI) aims to generate predictive frames by motion-warping from bidirectional refer- ences. Most examples of VFI utilize spatiotemporal semantic information to realize motion estimation and interpolation. However, due to variable acceleration, irregular movement trajectories, and camera movement in real-world cases, they can not be sufficient to deal with non-linear middle frame estimation. In this paper, we present a reformulation of the VFI as a joint non-linear motion regression (JNMR) strategy to model the complicated inter-frame motions. Specifically, the motion trajectory between the target frame and multiple reference frames is regressed by a temporal concatenation of multi-stage quadratic models. Then, a comprehensive joint distribution is constructed to connect all temporal motions. Moreover, to reserve more contextual details for joint regression, the feature learning network is devised to explore clarified feature expressions with dense skip- connection. Later, a coarse-to-fine synthesis enhancement module is utilized to learn visual dynamics at different resolutions with multi-scale textures. The experimental VFI results show the effectiveness and significant improvement of joint motion regression over the state-of-the-art methods. 

## Pipeline
<div class="row" align=center>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/JNMRchat.jpg" title="JNMR" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
     Illustration of JNMR structure details. Here, we incorporate temporal-aware motion sequences to model different quadratic regressions for the middle motions. Thus, the entire model is regressed by optimizing each individual sub-non-linear model.
</div>

## Highlights
1. We propose a joint multi-variable non-linear motion regression strategy for motion compensation of VFI. The refined interpolation modeling can reconstruct the actual kinematic characteristics among large and complicated motions.

2. We leverage ConvLSTM to realize the joint multi-stage quadratic model for JNMR, which enhances the temporal consistency in inter-frame prediction.

3. We design the regression-driven feature learning module and coarse-to-fine enhancement module, separately opti- mizing the feature extraction with competitive parameters and pleasing visual qualities on different resolutions.

## Results
<div class="row" align=center>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/JNMRTable.jpg" title="JNMRTable" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row" align=center>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/JNMRfig.jpg" title="JNMRfig" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Materials


[paper](https://yaochao1986.github.io/assets/pdf/TIP2023-JNMR_Joint_Non-Linear_Motion_Regression_for_Video_Frame_Interpolation.pdf) 
[Code](https://github.com/ruhig6/JNMR)

## Citation
{% raw %}

```
@article{liu2023JNMR,
  title={JNMR: Joint Non-Linear Motion Regression for Video Frame Interpolation},
  author={Liu, Meiqin and Xu, Chenming and Yao, Chao and Lin, Chunyu and Zhao, Yao},
  journal={IEEE Transactions on Image Processing},
  volume={32},
  number={},
  pages={5283--5295},
  year={2023},
  publisher={IEEE}
}
```

{% endraw %}
## Contact

If you have any questions, please contact Chao Yao at yaochao@ustb.edu.cn
