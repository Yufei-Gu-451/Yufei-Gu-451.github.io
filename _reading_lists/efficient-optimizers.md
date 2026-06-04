---
title: Efficient Optimizers — Paper List
subtitle: Memory- and compute-efficient optimizers for deep learning and LLM training.
status: active
date: 2026-06-04
---

## Overview

1. *Gradient Descent Happens in a Tiny Subspace.* [\<arXiv 2018.12\>](https://arxiv.org/pdf/1812.04754)
2. *From SGD to Spectra: A Theory of Neural Network Weight Dynamics.* [\<arXiv 2025.7\>](https://arxiv.org/pdf/2507.12709)
3. *Cerebras-GPT: Open Compute-Optimal Language Models Trained on the Cerebras Wafer-Scale Cluster.* [\<arXiv 2023.4\>](https://arxiv.org/pdf/2304.03208)

## Pre-Training

1. *Fantastic Pretraining Optimizers and Where to Find Them.* [\<arXiv 2025.9\>](https://arxiv.org/abs/2509.02046)
2. *Benchmarking Optimizers for Large Language Model Pretraining.* [\<arXiv 2025.7\>](https://arxiv.org/abs/2509.01440)
3. *Hyperparameter Transfer Enables Consistent Gains of Matrix-Preconditioned Optimizers Across Scales.* [\<arXiv 2025.12\>](https://arxiv.org/pdf/2512.05620)
4. *When is Warmstarting Effective for Scaling Language Models?* [\<arXiv 2026.5\>](https://arxiv.org/pdf/2605.13405)

## Post-Training

1. *Optimizer-Model Consistency: Full Finetuning with the Same Optimizer as Pretraining Forgets Less.* [\<arXiv 2026.5\>](https://arxiv.org/pdf/2605.06654)
2. *Can Muon Fine-tune Adam-Pretrained Models?* [\<arXiv 2026.5\>](https://arxiv.org/abs/2605.10468)

## Adam and its Variants

1. *Adam: A Method for Stochastic Optimization.* ICLR 2015.
    - *Adam Accumulation to Reduce Memory Footprints of both Activations and Gradients for Large-scale DNN Training.* [\<ICLR 2023 Reject\>](https://openreview.net/forum?id=9eT2pA9P-vI)
    - *Adam-mini: Use Fewer Learning Rates to Gain More.* ICLR 2025. [\<arXiv 2024.6\>](https://arxiv.org/abs/2406.16793)
    - *Pre-Training LLMs on a Budget: A Comparison of Three Optimizers.* [\<arXiv 2025.7\>](https://arxiv.org/abs/2507.08472v1)
    - *The Sharpness Disparity Principle in Transformers for Accelerating Language Model Pre-Training.* [\<ICML 2025\>](https://arxiv.org/abs/2502.19002)

## Modern Optimizers

1. *AdaGrad: Adaptive Subgradient Methods for Online Learning and Stochastic Optimization.* JMLR 2011.
    - *AdaHessian: An Adaptive Second Order Optimizer for Machine Learning.* [\<AAAI 2021\>](https://ojs.aaai.org/index.php/AAAI/article/view/17275)
    - *Adafactor: Adaptive Learning Rates with Sublinear Memory Cost.* [\<ICML 2018\>](http://proceedings.mlr.press/v80/shazeer18a.html)
        - *Scaling Vision Transformers.* CVPR 2022.
        - *Deconstructing What Makes a Good Optimizer for Language Models.* CoLR 2024.
2. *K-FAC: Optimizing Neural Networks with Kronecker-factored Approximate Curvature.* [\<ICML 2015\>](https://proceedings.mlr.press/v37/martens15.html)
    - *Eva: Practical Second-order Optimization with Kronecker-vectorized Approximation.* [\<ICLR 2023\>](https://openreview.net/forum?id=_Mic8V96Voy)
3. *Lion: Symbolic Discovery of Optimization Algorithms.* [\<NIPS 2023\>](https://proceedings.neurips.cc/paper_files/paper/2023/hash/9a39b4925e35cf447ccba8757137d84f-Abstract-Conference.html)
    - *OLion: Approaching the Hadamard Ideal by Intersecting Spectral and Implicit Biases.* [\<arXiv 2026.2\>](https://arxiv.org/abs/2602.01105)
4. *Sophia: A Scalable Stochastic Second-Order Optimizer for Language Model Pre-Training.* [\<ICLR 2024\>](https://iclr.cc/virtual/2024/poster/19488)
5. *MARS: Unleashing the Power of Variance Reduction for Training Large Models.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2411.10438)
6. *Preconditioned Inexact Stochastic ADMM for Deep Models.* [\<Nature Machine Intelligence\>](https://www.nature.com/articles/s42256-026-01182-3.pdf)

## Spectral Optimizers

1. *Shampoo: Preconditioned Stochastic Tensor Optimization.* [\<ICML 2018\>](https://proceedings.mlr.press/v80/gupta18a)
    - *Scalable Second Order Optimization for Deep Learning.* [\<arXiv 2020\>](https://arxiv.org/abs/2002.09018)
    - *A Distributed Data-Parallel PyTorch Implementation of the Distributed Shampoo Optimizer for Training Neural Networks At-Scale.* [\<arXiv 2023.9\>](https://arxiv.org/abs/2309.06497)
        - *DASH: Faster Shampoo via Batched Block Preconditioning and Efficient Inverse-Root Solvers.* [\<arXiv 2026.2\>](https://arxiv.org/pdf/2602.02016)
    - *When Does Second-Order Optimization Speed Up Training?* [\<ICLR 2024 Tiny\>](https://iclr.cc/virtual/2024/20933)
    - *SOAP: Improving and Stabilizing Shampoo using Adam.* [\<NIPS 2024 Workshop\>](https://nips.cc/virtual/2024/100406) [\<arXiv\>](https://arxiv.org/abs/2409.11321)
        - *Improving SOAP using Iterative Whitening and Muon.* [\<GitHub 2025\>](https://nikhilvyas.github.io/SOAP_Muon.pdf)
    - *Conda: Column-Normalized Adam for Training Large Language Models Faster.* [\<arXiv 2025.9\>](https://arxiv.org/abs/2509.24218)
2. *Muon: An Optimizer for the Hidden Layers of Neural Networks.* [\<GitHub 2024\>](https://github.com/KellerJordan/Muon) [\<Blog\>](https://kellerjordan.github.io/posts/muon/)
    - *Muon is Scalable for LLM Training.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.16982)
    - *Practical Efficiency of Muon for Pretraining.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.02222v1)
    - **Follow-up Optimizers:**
        - *AdaMuon: Adaptive Muon Optimizer.* [\<arXiv 2025.7\>](https://arxiv.org/abs/2507.11005)
        - *Tensorized Orthonormalization Beyond Layer-Wise Muon for Large Language Model Pre-Training.* [\<arXiv 2026.1\>](https://arxiv.org/pdf/2601.23261)
        - *The Polar Express: Optimal Matrix Sign Methods and their Application to the Muon Algorithm.* [\<ICLR 2026 Oral\>](https://openreview.net/forum?id=yRtgZ1K8hO)
        - *HTMuon: Improving Muon via Heavy-Tailed Spectral Correction.* [\<arXiv 2026.3\>](https://arxiv.org/pdf/2603.10067)
        - *Muon²: Boosting MUON via Adaptive Second-Moment Preconditioning.* [\<arXiv 2026.4\>](https://arxiv.org/abs/2604.09967)
        - *AMO: Adaptive Muon Orthogonalization.* [\<arXiv 2026.5\>](https://arxiv.org/pdf/2605.17806)
    - **Theory / Analytics:**
        - *Isotropic Curvature Model for Understanding Deep Learning Optimization: Is Gradient Orthogonalization Optimal?* [\<arXiv 2025.11\>](https://arxiv.org/abs/2511.00674)
        - *Preconditioning Benefits of Spectral Orthogonalization in Muon.* [\<arXiv 2026.1\>](https://arxiv.org/pdf/2601.13474)
        - *Spectral Flattening Is All Muon Needs: How Orthogonalization Controls Learning Rate and Convergence.* [\<arXiv 2026.5\>](https://arxiv.org/pdf/2605.13079)
        - *Muon is Not That Special: Random or Inverted Spectra Work Just as Well.* [\<arXiv 2026.5\>](https://arxiv.org/abs/2605.11181)

## Optimizer Wrappers / Decorators

1. *Cautious Optimizers: Improving Training with One Line of Code.* [\<arXiv 2024.11\>](https://arxiv.org/abs/2411.16085)
    - *Cautious Weight Decay.* [\<arXiv 2025.10\>](https://arxiv.org/abs/2510.12402)
2. *GradPower: Powering Gradients for Faster Language Model Pre-Training.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.24275)
3. *On Surprising Effectiveness of Masking Updates in Adaptive Optimizers.* [\<arXiv 2026.2\>](https://arxiv.org/abs/2602.15322)

## Norm-Constrained Optimization

1. *μP: A Spectral Condition for Feature Learning.* [\<arXiv 2023.10\>](https://arxiv.org/abs/2310.17813)
2. *Scion: Training Deep Learning Models with Norm-Constrained LMOs.* [\<ICML 2025 Spotlight\>](https://arxiv.org/abs/2502.07529)
    - *Generalized Gradient Norm Clipping & Non-Euclidean (L0, L1)-Smoothness.* [\<NIPS 2025 Oral\>](https://arxiv.org/abs/2506.01913)
    - *Scale-Invariant Neural Network Optimization: Norm Geometry and Heavy-Tailed Noise.* [\<arXiv 2026.5\>](https://arxiv.org/pdf/2605.18528)
3. *Swan: SGD with Normalization and Whitening Enables Stateless LLM Training.* [\<arXiv 2024.12\>](https://arxiv.org/abs/2412.13148)
    - *SinkGD: Gradient Multi-Normalization for Stateless and Scalable LLM Training.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.06742)
    - *ARO: A New Lens On Matrix Optimization For Large Models.* [\<arXiv 2026.2\>](https://arxiv.org/abs/2602.09006)
4. *On the Width Scaling of Neural Optimizers Under Matrix Operator Norms.* [\<arXiv 2026.3\>](https://arxiv.org/abs/2603.09952)
    - *RMNP: Row-Momentum Normalized Preconditioning for Scalable Matrix-Based Optimization.* [\<arXiv 2026.3\>](https://arxiv.org/pdf/2603.20527)
    - *MUON+: Towards Better Muon via One Additional Normalization Step.* [\<arXiv 2026.2\>](https://arxiv.org/abs/2602.21545)
    - *Nora: Normalized Orthogonal Row Alignment for Scalable Matrix Optimizer.* [\<arXiv 2026.5\>](https://arxiv.org/abs/2605.03769)
    - *Normuon: Making Muon More Efficient and Scalable.* [\<ICML 2026 Spotlight\>](https://arxiv.org/abs/2510.05491)
        - *Aurora: A Leverage-Aware Optimizer for Rectangular Matrices.* [\<Blog 2026.5\>](https://blog.tilderesearch.com/blog/aurora)

## Weight Norm Control

1. *Hyperball Optimization.* [\<Notion 2026.1\>](https://psychedelic-sunstone-851.notion.site/Fantastic-Pretraining-Optimizers-and-Where-to-Find-Them-2-1-Hyperball-Optimization-2e924306e6f280e7a5ffee00eb40a0dd)
    - *Rethinking Language Model Scaling under Transferable Hypersphere Optimization.* [\<arXiv 2026.4\>](https://arxiv.org/abs/2603.28743)
2. *SSO: Controlled LLM Training on Spectral Sphere.* [\<arXiv 2026.1\>](https://arxiv.org/abs/2601.08393)
    - *MCSD: Manifold Constrained Steepest Descent.* [\<arXiv 2026.1\>](https://arxiv.org/abs/2601.21487)
    - *Scale-Invariant Neural Network Optimization: Norm Geometry and Heavy-Tailed Noise.* [\<arXiv 2026.5\>](https://arxiv.org/abs/2605.18528)
3. *Muown: Row-Norm Control for Muon Optimization.* [\<arXiv 2026.5\>](https://arxiv.org/pdf/2605.10797v1)

## Manifold & Architecture-Optimizer Co-design

1. *Modular Manifolds.* [\<Jeremy Bernstein 2025.9\>](https://thinkingmachines.ai/blog/modular-manifolds/#modular-manifolds)
2. *Symmetry-Compatible Principle for Optimizer Design: Embeddings, LM Heads, SwiGLU MLPs, and MoE Routers.* [\<arXiv 2026.5\>](https://arxiv.org/pdf/2605.18106)

## Low-Rank Subspace Optimizers

1. *APOLLO: SGD-like Memory, AdamW-level Performance.* [\<arXiv 2024.12\>](https://arxiv.org/abs/2412.05270)
2. *Taming Momentum: Rethinking Optimizer States Through Low-Rank Approximation.* [\<ICLR 2026 Oral\>](https://openreview.net/forum?id=9Q0dNBYeEY)
3. *A Memory Efficient Randomized Subspace Optimization Method for Training Large Language Models.* ICML 2025. [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.07222)
4. *NuMuon: Nuclear-Norm-Constrained Muon for Compressible LLM Training.* [\<arXiv 2026.3\>](https://arxiv.org/abs/2603.03597v1)

## LoRA / GaLoRA

1. *InRank: Incremental Low-Rank Learning.* [\<arXiv 2023.6\>](https://arxiv.org/abs/2306.11250)
2. *GaLore: Memory-Efficient LLM Training by Gradient Low-Rank Projection.* [\<ICML 2024\>](https://openreview.net/forum?id=hYHsrKDiX7)
    - *GaLore 2: Large-Scale LLM Pre-Training by Gradient Low-Rank Projection.* [\<arXiv 2025.4\>](https://arxiv.org/abs/2504.20437v1)
    - *LDAdam: Adaptive Optimization from Low-Dimensional Gradient Statistics.* [\<ICLR 2025\>](https://openreview.net/forum?id=Zkp1GuHerF)
    - *SEPARATE: A Simple Low-rank Projection for Gradient Compression in Modern Large-scale Model Training Process.* [\<ICLR 2025\>](https://openreview.net/forum?id=8HuLgtjqOD)
3. *Mixture-of-Subspaces in Low-Rank Adaptation.* [\<arXiv 2024.6\>](https://arxiv.org/abs/2406.11909)
4. *On the Optimization Landscape of Low-Rank Adaptation Methods for Large Language Models.* [\<ICLR 2025\>](https://openreview.net/forum?id=pxclAomHat)
5. *Make LoRA Great Again: Boosting LoRA with Adaptive Singular Values and Mixture-of-Experts Optimization Alignment.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.16894)
6. *Fira: Can We Achieve Full-rank Training of LLMs Under Low-rank Constraint?* [\<arXiv 2024.10\>](https://arxiv.org/abs/2410.01623)
7. *FRUGAL: Memory-Efficient Optimization by Reducing State Overhead for Scalable Training.* [\<ICML 2025\>](https://openreview.net/forum?id=B4TyAILcE4)
8. *LoRA Training Provably Converges to a Low-Rank Global Minimum or It Fails Loudly (But it Probably Won't Fail).* [\<ICML 2025 Oral\>](https://openreview.net/attachment?id=o9zDYV4Ism&name=pdf)
9. *Riemannian Optimization for LoRA on the Stiefel Manifold.* [\<arXiv 2025.8\>](https://arxiv.org/abs/2508.17901)
10. *QR-LoRA: QR-Based Low-Rank Adaptation for Efficient Fine-Tuning of Large Language Models.* [\<arXiv 2025.8\>](https://arxiv.org/abs/2508.21810v1)
