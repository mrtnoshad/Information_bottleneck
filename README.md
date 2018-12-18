# Information Bottleneck Estimation in Deep Learning 
Estimation of Information Bottleneck in Deep Neural Networks

## Description
Thanks to EDGE, a recently proposed scalable and optimal estimator of Mutual Information, It is shown that the Information Bottleneck theory of deep learning, proposed by Naftali Tishby, applies for a wide range of activations such as ReLU and Maxpooling!
https://arxiv.org/pdf/1801.09125.pdf

## Estimator Used
EDGE: Ensemble Dependence Graph Estimator
https://github.com/mrtnoshad/EDGE

## Abstract of the paper
The Mutual Information (MI) is an often used measure of dependency between two random variables utilized in information theory, statistics and machine learning. Recently several MI estimators have been proposed that can achieve parametric MSE convergence rate. However, most of the previously proposed estimators have the high computational complexity of at least O(N2). We propose a unified method for empirical non-parametric estimation of general MI function between random vectors in ℝd based on N i.i.d. samples. The reduced complexity MI estimator, called the ensemble dependency graph estimator (EDGE), combines randomized locality sensitive hashing (LSH), dependency graphs, and ensemble bias-reduction methods. We prove that EDGE achieves optimal computational complexity O(N), and can achieve the optimal parametric MSE rate of O(1/N) if the density is d times differentiable. To the best of our knowledge EDGE is the first non-parametric MI estimator that can achieve parametric MSE rates with linear time complexity. We illustrate the utility of EDGE for the analysis of the information plane (IP) in deep learning. Using EDGE we shed light on a controversy on whether or not the compression property of information bottleneck (IB) in fact holds for ReLu and other rectification functions in deep neural networks (DNN).

