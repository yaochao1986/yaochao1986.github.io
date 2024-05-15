---
layout: post
title:  Normalizing Flow and Invertible Networks
date:   2023-12-10 16:20:36
description: overview
tags: paper
categories: sample-posts
---

# 标准化流（Normalizing Flows）

利用深度模型根据万能逼近定理是可以接近真实数据的样本分布的，但实际上在具体应用中还差的很远。我们需要什么样的分布，既要具有接近真实样本的表达能力，又要具有统计机器学习模型较好的解释性。

思索片刻，我们想起了“亲密战友”高斯分布。优点很多，包括采样方便、解析的密度已知、KL距离容易计算，还有中心极限定理的保证，任何大的数据都趋近于高斯分布，所以你怎么用它都对！更别提重参数化技巧啦，你还能梯度反传。

