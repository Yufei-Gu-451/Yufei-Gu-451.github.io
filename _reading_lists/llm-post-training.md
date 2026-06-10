---
title: LLM Post Training & Reasoning — Paper List
subtitle: Methodology, techniques, and problem settings for LLM reasoning, alignment, efficiency, latent reasoning, attention sinks, and quantization.
status: active
date: 2026-05-31
---

## Methodology / Techniques

1. **Prompts / Thoughts Engineering:**
    - *Chain-of-Thought Prompting Elicits Reasoning in Large Language Models.* [\<NIPS 2022\>](https://proceedings.neurips.cc/paper/2022/file/9d5609613524ecf4f15af0f7b31abca4-Paper-Conference.pdf)
    - *Tree of Thoughts: Deliberate Problem Solving with Large Language Models.* [\<NIPS 2023\>](https://proceedings.neurips.cc/paper_files/paper/2023/file/271db9922b8d1f4dd7aaef84ed5ac703-Paper-Conference.pdf)
    - *Graph of Thoughts: Solving Elaborate Problems with Large Language Models.* [\<AAAI 2024\>](https://ojs.aaai.org/index.php/AAAI/article/view/29720/31236)
    - *Chain-of-Thought Reasoning Without Prompting.* [\<NeurIPS 2024\>](https://arxiv.org/pdf/2402.10200.pdf)
    - *Unlocking the Capabilities of Thought: A Reasoning Boundary Framework to Quantify and Optimize Chain-of-Thought.* [\<NIPS 2024 Oral\>](https://arxiv.org/pdf/2410.05695)
    - *Buffer of Thoughts: Thought-Augmented Reasoning with Large Language Models.* [\<NIPS 2024 Spotlight\>](https://arxiv.org/pdf/2406.04271)
2. **Retrieval Augmented Generation (RAG):**
    - *Measuring and Enhancing Trustworthiness of LLMs in RAG through Grounded Attributions and Learning to Refuse.* [\<ICLR 2025 Oral\>](https://openreview.net/forum?id=Iyrtb9EJBp)
3. **Test-Time Training:**
    - *Test-Time Training with Self-Supervision for Generalization under Distribution Shifts.* [\<ICML 2020\>](https://proceedings.mlr.press/v119/sun20b/sun20b.pdf)
    - *Towards Understanding Multi-Task Learning (Generalization) of LLMs via Detecting and Exploring Task-Specific Neurons.* [\<arXiv 2024\>](https://arxiv.org/pdf/2407.06488)
    - *The Surprising Effectiveness of Test-Time Training for Abstract Reasoning.* [\<arXiv 2024\>](https://ekinakyurek.github.io/papers/ttt.pdf)
    - *LIMA: Less Is More for Alignment.* [\<NIPS 2023\>](https://proceedings.neurips.cc/paper_files/paper/2023/hash/ac662d74829e4407ce1d126477f4a03a-Abstract-Conference.html)
4. **Test-Time Scaling:**
    - *s1: Simple Test-Time Scaling.* [\<arXiv 2025.1\>](https://arxiv.org/abs/2501.19393)
    - *LIMO: Less is More for Reasoning.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.03387)
    - *Small Models Struggle to Learn from Strong Reasoners.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.12143)
    - *Self-rewarding Correction for Mathematical Reasoning.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.19613)
    - *Efficient Test-Time Scaling via Self-Calibration.* [\<arXiv 2025.2\>](https://export.arxiv.org/abs/2503.00031)
5. **Long / Short CoT:**
    - *Demystifying Long Chain-of-Thought Reasoning in LLMs.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.03373)
    - *Stepwise Perplexity-Guided Refinement for Efficient Chain-of-Thought Reasoning in Large Language Models.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.13260)
    - *When More is Less: Understanding Chain-of-Thought Length in LLMs.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.07266)
    - *TokenSkip: Controllable Chain-of-Thought Compression in LLMs.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.12067)
    - *How Well do LLMs Compress Their Own Chain-of-Thought? A Token Complexity Approach.* [\<arXiv 2025.3\>](https://arxiv.org/abs/2503.01141)
    - *DAST: Difficulty-Adaptive Slow-Thinking for Large Reasoning Models.* [\<arXiv 2025.3\>](https://arxiv.org/abs/2503.04472)
    - *Unlocking Efficient Long-to-Short LLM Reasoning with Model Merging.* [\<arXiv 2025.3\>](https://arxiv.org/abs/2503.20641)
    - *Critical Thinking: Which Kinds of Complexity Govern Optimal Reasoning Length?* [\<arXiv 2025.4\>](https://arxiv.org/abs/2504.01935v1)
    - *Condensed Reasoning Prompting: Efficient Strategies, Evaluations, and Trade Offs in Large Language Model Reasoning.*
    - *Dynamic Early Exit in Reasoning Models.* arXiv 2025.4.
6. **Latent Reasoning:**
    - *COCONUT: Training Large Language Models to Reason in a Continuous Latent Space.* [\<arXiv 2024.12\>](https://arxiv.org/abs/2412.06769)
    - *LLMs Do Not Think Step-by-step In Implicit Reasoning.* [\<arXiv 2024.11\>](https://arxiv.org/abs/2411.15862)
    - *Training Large Language Models to Reason in a Continuous Latent Space.* [\<ICLR 2025 Reject\>](https://openreview.net/forum?id=tG4SgayTtk)
    - *Reasoning with Latent Thoughts: On the Power of Looped Transformers.* [\<ICLR 2025\>](https://openreview.net/forum?id=din0lGfZFd)
    - *Scaling up Test-Time Compute with Latent Reasoning: A Recurrent Depth Approach.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.05171)
    - *Reasoning Models Don't Always Say What They Think.* [\<2025.4\>](https://assets.anthropic.com/m/71876fabef0f0ed4/original/reasoning_models_paper.pdf)
    - *Reasoning Models Can Be Effective Without Thinking.* [\<arXiv 2025.4\>](https://arxiv.org/abs/2504.09858)
    - *Enhancing Latent Computation in Transformers with Latent Tokens.*
    - *Seek in the Dark: Reasoning via Test-Time Instance-Level Policy Gradient in Latent Space.*
    - *Continuous Chain of Thought Enables Parallel Exploration and Reasoning.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.23648v1)
    - *Multimodal Chain of Continuous Thought for Latent-Space Reasoning in Vision-Language Models.* [\<arXiv 2025.8\>](https://arxiv.org/abs/2508.12587v1)
7. **Reinforcement Learning:**
    - *DeepScaleR: Surpassing O1-Preview with a 1.5B Model by Scaling RL.* [\<Notion 2025\>](https://pretty-radio-b75.notion.site/DeepScaleR-Surpassing-O1-Preview-with-a-1-5B-Model-by-Scaling-RL-19681902c1468005bed8ca303013a4e2)
    - *Logic-RL: Unleashing LLM Reasoning with Rule-Based Reinforcement Learning.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.14768)
    - *Reinforcement Learning for Reasoning in Small LLMs: What Works and What Doesn't.* [\<arXiv 2025.3\>](https://arxiv.org/abs/2503.16219)
    - *AceReason-Nemotron: Advancing Math and Code Reasoning through Reinforcement Learning.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.16400v1)
    - *Incorrect Baseline Evaluations Call into Question Recent LLM-RL Claims.* [\<Notion 2025.5\>](https://safe-lip-9a8.notion.site/Incorrect-Baseline-Evaluations-Call-into-Question-Recent-LLM-RL-Claims-2012f1fbf0ee8094ab8ded1953c15a37)
        - *Reinforcement Learning for Reasoning in Large Language Models with One Training Example.* [\<arXiv 2025.4\>](https://arxiv.org/abs/2504.20571)
        - *Learning to Reason without External Rewards.*
        - *Can Large Reasoning Models Self-Train?*
        - *Surrogate Signals from Format and Length: Reinforcement Learning for Solving Mathematical Problems without Ground Truth Answers.*
        - *The Unreasonable Effectiveness of Entropy Minimization in LLM Reasoning.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.15134v1)
    - *Implicit Reward as the Bridge: A Unified View of SFT and DPO Connections.* [\<arXiv 2025.7\>](https://arxiv.org/abs/2507.00018)
8. **LLM Agent:**
    - *Weak-for-Strong: Training Weak Meta-Agent to Harness Strong Executors.* [\<arXiv 2025.4\>](https://arxiv.org/abs/2504.04785v1)
9. **Quantization:**
    - *Quantitative Analysis of Performance Drop in DeepSeek Model Quantization.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.02390v1)
    - *An Empirical Study of Qwen3 Quantization.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.02214v1)
    - *Restructuring Vector Quantization with the Rotation Trick.* [\<ICLR 2025\>](https://proceedings.iclr.cc/paper_files/paper/2025/hash/2fefbb34af8008e81fb3f457fa5a2fc2-Abstract-Conference.html)
    - *GPLQ: A General, Practical, and Lightning QAT Method for Vision Transformers.* [\<NIPS 2025\>](https://openreview.net/forum?id=58Vr1KOWG9)
    - *Improving the Straight-Through Estimator with Zeroth-Order Information.* [\<NIPS 2025\>](https://openreview.net/forum?id=ceTeM2Xl1n)
    - *ParetoQ: Improving Scaling Laws in Extremely Low-bit LLM Quantization.* [\<arXiv 2025.10\>](https://arxiv.org/pdf/2502.02631v2)
    - *Lotion: Smoothing the Optimization Landscape for Quantized Training.* [\<arXiv 2025.10\>](https://arxiv.org/abs/2510.08757)
    - *CAGE: Curvature-Aware Gradient Estimation For Accurate Quantization-Aware Training.* [\<arXiv 2025.10\>](https://arxiv.org/abs/2510.18784)
    - *Outlier Smoothing with Closed-Form Rotations for W4A4 Large Language Model Quantization.* [\<arXiv 2025.11\>](https://arxiv.org/pdf/2511.22316v2)
    - *Towards Quantization-Aware Training for Ultra-Low-Bit Reasoning LLMs.* [\<ICLR 2026\>](https://openreview.net/forum?id=Azsd2qyK6C)
    - *Compute-Optimal Quantization-Aware Training.* [\<ICLR 2026\>](https://openreview.net/forum?id=QpbtT95S95)
    - *MixQuant: Pushing the Limits of Block Rotations in Post-Training Quantization.* [\<arXiv 2026.1\>](https://arxiv.org/pdf/2601.22347)
    - *HESTIA: A Hessian-Guided Differentiable Quantization-Aware Training Framework for Extremely Low-Bit LLMs.* [\<arXiv 2026.1\>](https://arxiv.org/pdf/2601.20745)
    - *D²Quant: Accurate Low-bit Post-Training Weight Quantization for LLMs.* [\<arXiv 2026.2\>](https://arxiv.org/abs/2602.02546)
    - *WinQ: Accelerating Quantization-Aware Training of Language Models Around Saddle Points.* [\<arXiv 2026.5\>](https://arxiv.org/pdf/2605.17471)

## Targets / Problem Settings

1. **Trustworthiness / Hallucination (Detection / Mitigation) by Entropy:**
    - *HaloScope: Harnessing Unlabeled LLM Generations for Hallucination Detection.* [\<NIPS 2024 Spotlight\>](https://arxiv.org/pdf/2409.17504)
    - *Semantic Entropy Probes: Robust and Cheap Hallucination Detection in LLMs.* [\<arXiv 2024\>](https://arxiv.org/pdf/2406.15927)
    - *LLMs Know More Than They Show: On the Intrinsic Representation of LLM Hallucinations.* [\<ICLR 2025\>](https://openreview.net/forum?id=KRnsX5Em3W)
    - *NoVo: Norm Voting off Hallucinations with Attention Heads in Large Language Models.* [\<ICLR 2025\>](https://openreview.net/forum?id=yaOe2xBcLC)
    - *DoLa: Decoding by Contrasting Layers Improves Factuality in Large Language Models.* [\<ICLR 2025\>](https://openreview.net/forum?id=Th6NyL07na)
    - *Teaching Language Models to Hallucinate Less with Synthetic Tasks.* [\<ICLR 2025\>](https://openreview.net/forum?id=xpw7V0P136)
    - *INSIDE: LLMs' Internal States Retain the Power of Hallucination Detection.* [\<ICLR 2025\>](https://openreview.net/forum?id=Zj12nzlQbz)
    - *Improving Reasoning Performance in Large Language Models via Representation Engineering.* [\<ICLR 2025\>](https://openreview.net/forum?id=IssPhpUsKt)
    - *Right Question is Already Half the Answer: Fully Unsupervised LLM Reasoning Incentivization.* arXiv 2025.4.
    - *Robust Hallucination Detection in LLMs via Adaptive Token Selection.* [\<arXiv 2025.4\>](https://arxiv.org/abs/2504.07863)
    - *TruthFlow: Truthful LLM Generation via Representation Flow Correction.* ICML 2025. [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.04556)
    - *The Entropy Mechanism of Reinforcement Learning for Reasoning Language Models.*
    - *How to Steer LLM Latents for Hallucination Detection?* ICML 2025.
    - *Can LLMs Lie? Investigation beyond Hallucination.*
    - *Why Language Models Hallucinate.* [\<OpenAI 2025.9\>](https://cdn.openai.com/pdf/d04913be-3f6f-4d2b-b283-ff432ef4aaa5/why-language-models-hallucinate.pdf)
2. **Alignment / Instruction Following:**
    - *Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To.* [\<ICLR 2025 Oral\>](https://openreview.net/forum?id=hTEGyKf0dZ)
    - *RAIN: Your Language Models Can Align Themselves without Finetuning.* [\<ICLR 2025\>](https://openreview.net/forum?id=pETSfWMUzy)
3. **Reward Model / LLM as a Judge:**
    - *Meta-Rewarding Language Models: Self-Improving Alignment with LLM-as-a-Meta-Judge.*
    - *Self-Preference Bias in LLM-as-a-Judge.* [\<arXiv 2024.10\>](https://arxiv.org/abs/2410.21819)
4. **Multi-task:**
    - *CoBa: Convergence Balancer for Multitask Finetuning of Large Language Models.* [\<EMNLP 2024 Oral\>](https://arxiv.org/abs/2410.06741)
    - *Unlocking the Power of Function Vectors for Characterizing and Mitigating Catastrophic Forgetting in Continual Instruction Tuning.* [\<ICLR 2025 Oral\>](https://openreview.net/forum?id=gc8QAQfXv6)
    - *Task-Adaptive Pretrained Language Models via Clustered-Importance Sampling.* [\<ICLR 2025\>](https://openreview.net/forum?id=p6ncr0eTKE)
    - *MTLoRA: Low-Rank Adaptation Approach for Efficient Multi-Task Learning.* [\<CVPR 2024\>](https://openaccess.thecvf.com/content/CVPR2024/html/Agiza_MTLoRA_Low-Rank_Adaptation_Approach_for_Efficient_Multi-Task_Learning_CVPR_2024_paper.html)
    - *Does Math Reasoning Improve General LLM Capabilities? Understanding Transferability of LLM Reasoning.* [\<arXiv 2025.7\>](https://arxiv.org/abs/2507.00432)
5. **Representation Engineering:**
    - *Is Bigger and Deeper Always Better? Probing LLaMA Across Scales and Layers.* [\<arXiv 2023.12\>](https://arxiv.org/abs/2312.04333)
    - *Does Representation Matter? Exploring Intermediate Layers in Large Language Models.* [\<arXiv 2024.12\>](https://arxiv.org/abs/2412.09563)
    - *Layer by Layer: Uncovering Hidden Representations in Language Models.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.02013)
    - *No Other Representation Component Is Needed: Diffusion Transformers Can Provide Representation Guidance by Themselves.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.02831v1)
6. **Theorem Proving:**
    - *LLM-based Automated Theorem Proving Hinges on Scalable Synthetic Data Generation.*

## Attention Sinks & Massive Values

1. *Massive Values in Self-Attention Modules are the Key to Contextual Knowledge Understanding.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.01563)
2. *What Drives Attention Sinks? A Study of Massive Activations and Rotational Positional Encoding in Large Vision-Language Models.* [\<IPM 2026\>](https://www.sciencedirect.com/science/article/pii/S0306457325003723)
3. *Context Tokens are Anchors: Understanding the Repeat Curse in dMLLMs from an Information Flow Perspective.* [\<ICLR 2026\>](https://openreview.net/forum?id=mOz9jVYxsD)
4. *Deconstructing Positional Information: From Attention Logits to Training Biases.* [\<ICLR 2026\>](https://openreview.net/forum?id=D0u0glT060)
5. *Massive Activations are the Key to Local Detail Synthesis in Diffusion Transformers.* [\<arXiv 2025.10\>](https://arxiv.org/abs/2510.11538)
6. *The Spike, the Sparse and the Sink: Anatomy of Massive Activations and Attention Sinks.* [\<arXiv 2026.3, Yann LeCun\>](https://arxiv.org/abs/2603.05498)
7. *Attention Sinks Are Provably Necessary in Softmax Transformers: Evidence from Trigger-Conditional Tasks.* [\<arXiv 2026.3\>](https://arxiv.org/abs/2603.11487)

## Latent Reasoning for AR/Diffusion-LLMs

1. **Auto-Regressive LLMs:**
    1. *COCONUT: Training Large Language Models to Reason in a Continuous Latent Space.* [\<arXiv 2024.12\>](https://arxiv.org/abs/2412.06769) [\<ICLR 2025 Reject\>](https://openreview.net/forum?id=tG4SgayTtk)
    2. *Deliberation in Latent Space via Differentiable Cache Augmentation.* [\<arXiv 2024.12\>](https://arxiv.org/abs/2412.17747)
    3. *SoftCoT: Soft Chain-of-Thought for Efficient Reasoning with LLMs.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.12134)
    4. *CODI: Compressing Chain-of-Thought into Continuous Space via Self-Distillation.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.21074)
    5. *Reasoning with Latent Thoughts: On the Power of Looped Transformers.* [\<ICLR 2025\>](https://openreview.net/forum?id=din0lGfZFd)
    6. *Reasoning to Learn from Latent Thoughts.* [\<arXiv 2025.3\>](https://arxiv.org/abs/2503.18866)
    7. *Scaling up Test-Time Compute with Latent Reasoning: A Recurrent Depth Approach.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.05171) [\<NIPS 2025\>](https://openreview.net/forum?id=S3GhJooWIC)
    8. *Think Silently, Think Fast: Dynamic Latent Compression of LLM Reasoning Chains.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.16552)
    9. *Enhancing Latent Computation in Transformers with Latent Tokens.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.12629)
    10. *Seek in the Dark: Reasoning via Test-Time Instance-Level Policy Gradient in Latent Space.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.13308)
    11. *Continuous Chain of Thought Enables Parallel Exploration and Reasoning.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.23648v1)
    12. *Latent Reasoning in LLMs as a Vocabulary-Space Superposition.* [\<arXiv 2025.10\>](https://arxiv.org/abs/2510.15522)
    13. *LaDiR: Latent Diffusion Enhances LLMs for Text Reasoning.* [\<arXiv 2025.10\>](https://arxiv.org/abs/2510.04573)
    14. *CLaRa: Bridging Retrieval and Generation with Continuous Latent Reasoning.* [\<arXiv 2025.11\>](https://arxiv.org/abs/2511.18659)
    15. *Hybrid Latent Reasoning via Reinforcement Learning.* [\<NIPS 2025 Spotlight\>](https://openreview.net/forum?id=LjtgTpWH71)
2. **Diffusion LLMs:**
    1. *Coevolutionary Continuous Discrete Diffusion: Make Your Diffusion Language Model a Latent Reasoner.* [\<arXiv 2025.10\>](https://arxiv.org/abs/2510.03206)
    2. *Soft-Masked Diffusion Language Models.* [\<arXiv 2025.10\>](https://arxiv.org/abs/2510.17206)
3. **Related:**
    1. *LLMs Do Not Think Step-by-step In Implicit Reasoning.* [\<arXiv 2024.11\>](https://arxiv.org/abs/2411.15862)
    2. *Reasoning Models Don't Always Say What They Think.* [\<arXiv 2025.4\>](https://assets.anthropic.com/m/71876fabef0f0ed4/original/reasoning_models_paper.pdf)
    3. *Reasoning Models Can Be Effective Without Thinking.* [\<arXiv 2025.4\>](https://arxiv.org/abs/2504.09858)


## Token-Level Iterative Refinement (AR/Diffusion)

1. *Token Assorted: Mixing Latent and Text Tokens for Improved Language Model Reasoning.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.03275)
2. *Mixture-of-Recursions: Learning Dynamic Recursive Depths for Adaptive Token-Level Computation.* [\<arXiv 2025.7\>](https://arxiv.org/abs/2507.10524)
3. *Reinforcing the Diffusion Chain of Lateral Thought with Diffusion Language Models.* [\<NIPS 2025\>](https://arxiv.org/abs/2505.10446)
    - *Path Planning for Diffusion Language Model Sampling.* [\<ICLR 2026 Review\>](https://openreview.net/forum?id=HVhr4EpSsh)
4. *Remasking Discrete Diffusion Models with Inference-Time Scaling.* [\<NIPS 2025\>](https://openreview.net/forum?id=IJryQAOy0p)
5. *Think-at-Hard: Selective Latent Iterations to Improve Reasoning Language Models.* [\<arXiv 2025.11\>](https://arxiv.org/abs/2511.08577)
6. *Beyond Masks: Efficient, Flexible Diffusion Language Models via Deletion-Insertion Processes.* [\<ICLR 2026 Review\>](https://openreview.net/forum?id=VbvXjs5f72)
7. *Don't Settle Too Early: Self-Reflective Remasking for Diffusion Language Models.* [\<ICLR 2026 Review\>](https://openreview.net/forum?id=BsZeTuB5fD)
8. *Latent Refinement Decoding: Enhancing Diffusion-Based Language Models by Refining Belief States.* [\<arXiv 2025.10\>](https://arxiv.org/abs/2510.11052) \<ICLR 2026 Review\>
9. *Learning Unmasking Policies for Diffusion Language Models.* [\<arXiv 2025.12\>](https://arxiv.org/abs/2512.09106v1)
10. *dUltra: Ultra-Fast Diffusion Language Models via Reinforcement Learning.* [\<arXiv 2025.12\>](https://arxiv.org/abs/2512.21446v1)

## Layer Skipping / Mixture-of-Depth

1. *Learning to Skip for Language Modeling.* [\<arXiv 2023.11\>](https://arxiv.org/abs/2311.15436)
2. *Not All Layers of LLMs are Necessary during Inference.* [\<arXiv 2024.3\>](https://arxiv.org/abs/2403.02181)
3. *LISA: Layerwise Importance Sampling for Memory-Efficient Large Language Model Fine-Tuning.* [\<NIPS 2024\>](https://proceedings.neurips.cc/paper_files/paper/2024/hash/687163285b8affc8ee933bdca8e75747-Abstract-Conference.html)
4. *Mixture-of-Depths: Dynamically Allocating Compute in Transformer-Based Language Models.* [\<arXiv 2024.4\>](https://arxiv.org/abs/2404.02258)
5. *Layer-wise Importance Matters: Less Memory for Better Performance in Parameter-efficient Fine-tuning of Large Language Models.* [\<arXiv 2024.10\>](https://arxiv.org/abs/2410.11772) [\<EMNLP 2024\>](https://aclanthology.org/2024.findings-emnlp.109/)
6. **Related:**
    - *Answer, Assemble, Ace: Understanding How LMs Answer Multiple Choice Questions.* [\<ICLR 2025 Spotlight\>](https://openreview.net/forum?id=6NNA0MxhCH)
    - *Determining Layer-wise Sparsity for Large Language Models Through a Theoretical Perspective.* [\<ICML 2025 Spotlight\>](https://openreview.net/forum?id=otNB7BzsiR)
    - *Do Language Models Use Their Depth Efficiently?* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.13898)
