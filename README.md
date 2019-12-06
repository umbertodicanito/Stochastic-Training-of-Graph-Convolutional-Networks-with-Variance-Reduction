# Stochastic Training of Graph Convolutional Networks with Variance Reduction

## Abstract
In this project, we analyzed the performance and behavior of a GCN (Graph
Convolutional Network). 
> All the project is based on the paper ’ Stochastic Training of Graph Convolutional Networks with Variance Reduction’ (Jianfei Chen, Jun Zhu, Le Song). The screenshot of the following images are taken from the paper.

![screenshot](https://github.com/umbertodicanito/Stochastic-Training-of-Graph-Convolutional-Networks-with-Variance-Reduction/blob/master/screenshot_preview.png)

In particular, in the original paper was been develop control variate based algorithms which allow sampling an arbitrarily small neighbor size; this because previous attempts on reducing the receptive field size by subsampling neighbors do not have a convergence guarantee, and their receptive field size per node is still in the order of hundreds.

## Dataset
In the original paper all the algorithms have been tested on six graph datasets (_Cora_, _PubMed_, _Citeseer_, _NELL_, _PPI_, _Reddit_).




