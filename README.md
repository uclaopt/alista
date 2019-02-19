# ALISTA: Analytic Weights Are As Good As Learned Weights in LISTA
This repository is for Analytic-LISTA networks proposed in the following paper:

[Jialin Liu\*](http://www.math.ucla.edu/~liujl11/pub.html),
[Xiaohan Chen\*](http://people.tamu.edu/~chernxh),
[Zhangyang Wang](http://www.atlaswang.com/) and
[Wotao Yin](http://www.math.ucla.edu/~wotaoyin/)
"ALISTA: Analytic Weights Are As Good As Learned Weights in LISTA", accepted at
ICLR 2019. The pdf can be found [here](https://openreview.net/pdf?id=B1lnzn0ctQ).

\*: These authors contributed equally and are listed alphabetically.

The code is tested in Linux environment (Python: 3.5.2, Tensorflow: 1.12.0,
CUDA9.0) with Nvidia GTX 1080Ti GPU.

## Introduction
Deep neural networks based on unfolding an iterative algorithm, for example,
LISTA (learned iterative shrinkage thresholding algorithm), have been an
empirical success for sparse signal recovery. The weights of these neural
networks are currently determined by data-driven “black-box” training. In this
work, we propose Analytic LISTA (ALISTA), where the weight matrix in LISTA is
computed as the solution to a data-free optimization problem, leaving only the
stepsize and threshold parameters to data-driven learning. This signiﬁcantly
simpliﬁes the training. Speciﬁcally, the data-free optimization problem is based
on coherence minimization. We show our ALISTA retains the optimal linear
convergence proved in (Chen et al., 2018) and has a performance comparable to
LISTA. Furthermore, we extend ALISTA to convolutional linear operators, again
determined in a data-free manner. We also propose a feed-forward framework that
combines the data-free optimization and ALISTA networks from end to end, one
that can be jointly trained to gain robustness to small perturbations in the
encoding model.

## Citation
If you find our code helpful in your resarch or work, please cite our paper.
```
@inproceedings{
liu2018alista,
title={{ALISTA}: Analytic Weights Are As Good As Learned Weights in {LISTA}},
author={Jialin Liu and Xiaohan Chen and Zhangyang Wang and Wotao Yin},
booktitle={International Conference on Learning Representations},
year={2019},
url={https://openreview.net/forum?id=B1lnzn0ctQ},
}
```
