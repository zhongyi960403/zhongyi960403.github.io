---
title: "A Continuous-Time Mirror Descent Approach to Sparse Phase Retrieval"
collection: publications
authors: "**F. Wu**, P. Rebeschini"
code: "https://github.com/fawuuu/mirror_spr"
excerpt: 'We analyze continuous-time mirror descent applied to sparse phase retrieval, which is the problem of recovering sparse signals from a set of magnitude-only measurements. We apply mirror descent to the unconstrained empirical risk minimization problem (batch setting), using the square loss and square measurements. We provide a convergence analysis of the algorithm in this non-convex setting and prove that, with the hypentropy mirror map, mirror descent recovers any $k$-sparse vector $\mathbf{x}^\star\in\mathbb{R}^n$ with minimum (in modulus) non-zero entry on the order of $\| \mathbf{x}^\star \|_2/\sqrt{k}$ from $k^2$ Gaussian measurements, modulo logarithmic terms. This yields a simple algorithm which, unlike most existing approaches to sparse phase retrieval, adapts to the sparsity level, without including thresholding steps or adding regularization terms. Our results also provide a principled theoretical understanding for Hadamard Wirtinger flow \citep{WR20}, as Euclidean gradient descent applied to the empirical risk problem with Hadamard parametrization can be recovered as a first-order approximation to mirror descent in discrete time.'
date: 2020-10-20
venue: 'Accepted for spotlight presentation at the 34th Conference on Neural Information Processing Systems (NeurIPS)'
paperurl: 'https://arxiv.org/abs/2010.10168'
proceedings: "https://papers.nips.cc/paper/2020/hash/e9470886ecab9743fb7ea59420c245d2-Abstract.html"
video: "https://videos.neurips.cc/search/A%20Continuous-Time%20Mirror%20Descent%20Approach%20to%20Sparse%20Phase%20Retrieval/video/slideslive-38937861"
---

