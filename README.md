# GaussianMixtureModel-clustering

From https://www.mathworks.com/matlabcentral/fileexchange/26184-em-algorithm-for-gaussian-mixture-model-em-gmm

Gaussian mixture model for clustering 

This package fits Gaussian mixture model (GMM) by expectation maximization (EM) algorithm.It works on data set of arbitrary dimensions. 

Several techniques are applied to improve numerical stability, such as computing probability in logarithm domain to avoid float number underflow which often occurs when computing probability of high dimensional data. 

The code is also carefully tuned to be efficient by utilizing vertorization and matrix factorization.
