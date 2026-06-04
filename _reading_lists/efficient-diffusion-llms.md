---
title: Efficient Diffusion Language Models — Paper List
subtitle: Inference acceleration, sampling, caching, and post-training techniques for diffusion language models.
status: archived
date: 2026-01-31
---

## Foundational Models

1. *LLaDA: Large Language Diffusion Models.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.09992) \<NIPS 2025 Oral\>
    - *LLaDA 1.5: Variance-Reduced Preference Optimization for Large Language Diffusion Models.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.19223)
2. *Dream: Diffusion Large Language Models.* [\<arXiv 2025.8\>](https://arxiv.org/abs/2508.15487)

## Analytics

1. *Diffusion Language Models Know the Answer Before Decoding.* [\<arXiv 2025.8\>](https://arxiv.org/abs/2508.19982)
2. *The Flexibility Trap: Why Arbitrary Order Limits Reasoning Potential in Diffusion Language Models.* [\<arXiv 2026.1\>](https://arxiv.org/pdf/2601.15165v1)
3. *Mechanism Shift During Post-training from Autoregressive to Masked Diffusion Language Models.* [\<arXiv 2026.1\>](https://arxiv.org/pdf/2601.14758v1)

## KV-Cache / Sparse Attention

1. *dKV-Cache: The Cache for Diffusion Language Models.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.15781v1)
2. *Fast-dLLM: Training-free Acceleration of Diffusion LLM by Enabling KV Cache and Parallel Decoding.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.22618)
3. *Sparse-dLLM: Accelerating Diffusion LLMs with Dynamic Cache Eviction.* [\<arXiv 2025.8\>](https://arxiv.org/abs/2508.02558v1)
4. *SparseD: Sparse Attention for Diffusion Language Models.* [\<arXiv 2025.9\>](https://arxiv.org/abs/2509.24014v1)
5. *dCache: Accelerating Diffusion-Based LLMs via Dual Adaptive Caching.* [\<arXiv 2025.9\>](https://arxiv.org/abs/2509.23094)
6. *Attention is All You Need for KV Cache in Diffusion LLMs.* [\<arXiv 2025.10\>](https://arxiv.org/abs/2510.14973)

## Step Distillation

1. *Progressive Distillation for Fast Sampling of Diffusion Models.* [\<ICLR 2022\>](https://arxiv.org/abs/2202.00512)
2. *Distillation of Discrete Diffusion through Dimensional Correlations.* [\<ICML 2025\>](https://openreview.net/forum?id=jCEl0aJpF6)
3. *Learning Few-Step Diffusion Models by Trajectory Distribution Matching.* [\<arXiv 2025.3\>](https://arxiv.org/abs/2503.06674)
4. *DLM-One: Diffusion Language Models for One-Step Sequence Generation.* [\<arXiv 2025.6\>](https://arxiv.org/pdf/2506.00290)
5. *Diffusion LLMs Can Do Faster-Than-AR Inference via Discrete Diffusion Forcing.* [\<arXiv 2025.8\>](https://arxiv.org/abs/2508.09192)
6. *FS-DFM: Fast and Accurate Long Text Generation with Few-Step Diffusion Language Models.* [\<arXiv 2025.9\>](https://arxiv.org/abs/2509.20624)
7. *Taming Masked Diffusion Language Models via Consistency Trajectory Reinforcement Learning with Fewer Decoding Steps.* [\<arXiv 2025.9\>](https://arxiv.org/abs/2509.23924)
8. **Adaptive (Block) Length:**
    - *CtrlDiff: Boosting Large Diffusion Language Models with Dynamic Block Prediction and Controllable Generation.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.14455)
    - *Beyond Fixed: Training-free Variable-Length Denoising for Diffusion Large Language Models.* [\<arXiv 2025.8\>](https://arxiv.org/abs/2508.00819)
    - *AdaBlock-dLLM: Semantic-Aware Diffusion LLM Inference via Adaptive Block Size.* [\<arXiv 2025.9\>](https://arxiv.org/abs/2509.26432)

## Training-free Sampler

1. *Accelerated Sampling from Masked Diffusion Models via Entropy Bounded Unmasking.* [\<arXiv 2025.5\>](https://arxiv.org/pdf/2505.24857)
2. *Wide-In, Narrow-Out: Revokable Decoding for Efficient and Effective DLLMs.* [\<arXiv 2025.7\>](https://arxiv.org/abs/2507.18578)
3. *Latent Refinement Decoding: Enhancing Diffusion-Based Language Models by Refining Belief States.* [\<arXiv 2025.10\>](https://arxiv.org/abs/2510.11052) \<ICLR 2026 Review\>
4. *KLASS: KL-Guided Fast Inference in Masked Diffusion Models.* [\<arXiv 2025.11\>](https://arxiv.org/abs/2511.05664)
5. *Beyond Confidence: Adaptive and Coherent Decoding for Diffusion Language Models.* [\<arXiv 2025.11\>](https://www.arxiv.org/abs/2512.02044)
6. *Optimal Inference Schedules for Masked Diffusion Models.* [\<arXiv 2025.11\>](https://arxiv.org/abs/2511.04647)
7. *Fast-Decoding Diffusion Language Models via Progress-Aware Confidence Schedules.* [\<arXiv 2025.12\>](https://arxiv.org/abs/2512.02892)
8. *Optimizing Decoding Paths in Masked Diffusion Models by Quantifying Uncertainty.* [\<arXiv 2025.12\>](https://arxiv.org/abs/2512.21336)
9. *Decoding Large Language Diffusion Models with Foreseeing Movement.* [\<arXiv 2025.12\>](https://arxiv.org/abs/2512.04135)

## Long Context

1. *LongLLaDA: Unlocking Long Context Capabilities in Diffusion LLMs.* [\<arXiv 2025.6\>](https://arxiv.org/abs/2506.14429)
2. *UltraLLaDA: Scaling the Context Length to 128k for Diffusion Large Language Models.* [\<arXiv 2025.10\>](https://arxiv.org/abs/2510.10481)

## Unmasking / Remasking

1. **Unmasking:**
    - *Reinforcing the Diffusion Chain of Lateral Thought with Diffusion Language Models.* [\<NIPS 2025\>](https://arxiv.org/abs/2505.10446)
        - *Path Planning for Diffusion Language Model Sampling.* [\<ICLR 2026 Review\>](https://openreview.net/forum?id=HVhr4EpSsh)
    - *Beyond Masks: Efficient, Flexible Diffusion Language Models via Deletion-Insertion Processes.* [\<ICLR 2026 Review\>](https://openreview.net/forum?id=VbvXjs5f72)
    - *Learning Unmasking Policies for Diffusion Language Models.* [\<arXiv 2025.12\>](https://arxiv.org/abs/2512.09106v1)
    - *dUltra: Ultra-Fast Diffusion Language Models via Reinforcement Learning.* [\<arXiv 2025.12\>](https://arxiv.org/abs/2512.21446v1)
    - *Beyond Hard Masks: Progressive Token Evolution for Diffusion Language Models.* [\<arXiv 2026.1\>](https://arxiv.org/abs/2601.07351)
2. **Remasking:**
    - *Remasking Discrete Diffusion Models with Inference-Time Scaling.* [\<NIPS 2025\>](https://openreview.net/forum?id=IJryQAOy0p)
    - *Don't Settle Too Early: Self-Reflective Remasking for Diffusion Language Models.* [\<ICLR 2026 Review\>](https://openreview.net/forum?id=BsZeTuB5fD)
    - *Saber: An Efficient Sampling with Adaptive Acceleration and Backtracking Enhanced Remasking for Diffusion Language Model.* [\<arXiv 2025.10\>](https://arxiv.org/abs/2510.18165)
    - *Thinking Inside the Mask: In-Place Prompting in Diffusion LLMs.* [\<arXiv 2025.8\>](https://arxiv.org/abs/2508.10736)

## AR-to-DLM Transfer / Transformation

1. *Autoregressive Models Rival Diffusion Models at ANY-ORDER Generation.* [\<arXiv 2026.1\>](https://arxiv.org/pdf/2601.13228v1)
2. *Mechanism Shift During Post-training from Autoregressive to Masked Diffusion Language Models.* [\<arXiv 2026.1\>](https://arxiv.org/pdf/2601.14758v1)
