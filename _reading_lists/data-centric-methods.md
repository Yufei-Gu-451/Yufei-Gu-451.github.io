---
title: Data-centric Methods — Paper List
subtitle: Data valuation, attribution, selection, pruning, and synthesis for deep learning and LLMs.
status: archived
date: 2025-09-01
---

## Data Valuation / Data Attribution

1. **Influence Functions:**
    - **General:**
        - *Understanding Black-box Predictions via Influence Functions.* Koh, 2017. [\<pdf\>](https://arxiv.org/pdf/1703.04730)
        - *Estimating Training Data Influence by Tracing Gradient Descent.* Garima, 2020. [\<pdf\>](https://proceedings.neurips.cc/paper_files/paper/2020/file/e6385d39ec9394f2f3a354d9d2b88eec-Paper.pdf)
        - *Multi-Stage Influence Function.* Chen, 2020. [\<pdf\>](https://arxiv.org/abs/2007.09081)
        - *Datamodels: Predicting Predictions from Training Data.* 2022.
        - *TRAK: Attributing Model Behavior at Scale.* [\<ICML 2023\>](https://proceedings.mlr.press/v202/park23c.html)
        - *Studying Large Language Model Generalization with Influence Functions.* Grosse, 2023. [\<pdf\>](https://arxiv.org/pdf/2308.03296)
        - *Channel-wise Influence: Effective Data Influence Estimation for Multivariate Time Series.* Wang, 2024. [\<pdf\>](https://arxiv.org/pdf/2408.14763)
        - *Scaling Laws for the Value of Individual Data Points in Machine Learning.* Covert, 2024. [\<ICML 2024\>](https://proceedings.mlr.press/v235/covert24a.html) [\<pdf\>](https://arxiv.org/pdf/2405.20456)
        - *The Mirrored Influence Hypothesis: Efficient Data Influence Estimation by Harnessing Forward Passes.* Ko, 2024. [\<CVPR 2024\>](https://openaccess.thecvf.com/content/CVPR2024/html/Ko_The_Mirrored_Influence_Hypothesis_Efficient_Data_Influence_Estimation_by_Harnessing_CVPR_2024_paper.html) [\<pdf\>](https://openaccess.thecvf.com/content/CVPR2024/papers/Ko_The_Mirrored_Influence_Hypothesis_Efficient_Data_Influence_Estimation_by_Harnessing_CVPR_2024_paper.pdf)
        - *Automated Efficient Estimation using Monte Carlo Efficient Influence Functions.* [\<NIPS 2024\>](https://papers.nips.cc/paper_files/paper/2024/hash/1d10fe211f5139de49f94c6f0c7cecbe-Abstract-Conference.html)
        - *Enhancing Training Robustness through Influence Measure.* [\<ICLR 2025\>](https://iclr.cc/virtual/2025/poster/30037)
        - *Capturing the Temporal Dependence of Training Data Influence.* [\<ICLR 2025 Oral\>](https://openreview.net/forum?id=uHLgDEgiS5)
    - **For LLM Pretraining:**
        - *What is Your Data Worth to GPT? LLM-Scale Data Valuation with Influence Functions.* Choe, 2024. [\<arXiv\>](https://arxiv.org/abs/2405.13954) [\<pdf\>](https://arxiv.org/pdf/2405.13954)
        - *Self-Influence Guided Data Reweighting for Language Model Pre-training.* Thakkar. [\<EMNLP 2023\>](https://openreview.net/forum?id=rXn9WO4M2p) [\<pdf\>](https://arxiv.org/pdf/2311.00913)
        - *MATES: Model-Aware Data Selection for Efficient Pretraining with Data Influence Models.* [\<NIPS 2024\>](https://arxiv.org/abs/2406.06046)
        - *Harnessing Diversity for Important Data Selection in Pretraining Large Language Models.* [\<ICLR 2025 Spotlight\>](https://openreview.net/forum?id=bMC1t7eLRc) [\<pdf\>](https://openreview.net/pdf?id=bMC1t7eLRc)
        - *Scalable Influence and Fact Tracing for Large Language Model Pretraining.* [\<ICLR 2025\>](https://openreview.net/forum?id=gLa96FlWwn) [\<pdf\>](https://arxiv.org/pdf/2408.03560)
        - *AttentionInfluence: Adopting Attention Head Influence for Weak-to-Strong Pretraining Data Selection.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.07293v1)
    - **For LLM Fine-tuning:**
        - *Empirical Influence Functions to Understand the Logic of Fine-tuning.* Matelsky, 2024. [\<pdf\>](https://arxiv.org/pdf/2406.00509)
        - *In2Core: Leveraging Influence Functions for Coreset Selection in Instruction Finetuning of Large Language Models.* Joaquin, 2024. [\<pdf\>](https://arxiv.org/pdf/2408.03560)
        - *IDEAL: Influence-Driven Selective Annotations Empower In-Context Learners In Large Language Models.* Zhang. [\<ICLR 2024\>](https://openreview.net/forum?id=Spp2i1hKwV)
        - *DATAINF: Efficiently Estimating Data Influence in LoRA-Tuned LLMs and Diffusion Models.* Kwon. [\<ICLR 2024\>](https://openreview.net/forum?id=9m02ib92Wz) [\<pdf\>](https://openreview.net/attachment?id=9m02ib92Wz&name=pdf)
        - *LESS: Selecting Influential Data for Targeted Instruction Tuning.* Xia. [\<ICLR 2024 Workshop\>](https://iclr.cc/virtual/2024/22436) [\<pdf\>](https://arxiv.org/pdf/2402.04333)
    - **For LLM Reasoning:**
        - *What Kind of Pretraining Data Do Large Language Models Rely on When Doing Reasoning?* [\<ICLR 2025\>](https://iclr.cc/virtual/2025/poster/31190)
            - *Procedural Knowledge in Pretraining Drives Reasoning in Large Language Models.* [\<arXiv 2024.11\>](https://arxiv.org/abs/2411.12580)
        - *Influence Functions for Efficient Data Selection in Reasoning.*
    - **ICLR 2025 Withdrawn / Reject:**
        - *Do Influence Functions Work on Large Language Models?* [\<pdf\>](https://openreview.net/pdf?id=hnsiuIcRT7)
        - *Large-scale Training Data Attribution with Efficient Influence Functions.* [\<pdf\>](https://openreview.net/pdf?id=jZw0CWXuDc)
        - *Understanding Impact of Human Feedback via Influence Functions.* [\<pdf\>](https://openreview.net/pdf?id=dTQmayPKMs)
        - *Revisit, Extend, and Enhance Hessian-free Influence Functions.* [\<pdf\>](https://openreview.net/pdf?id=WT2bL7sCM1)
        - *Revisiting Inverse Hessian Vector Products for Calculating Influence Functions.* [\<pdf\>](https://openreview.net/pdf?id=s6nYndMwG7)
2. **Data Behaviour in Training:**
    - *An Empirical Study of Example Forgetting During Deep Neural Network Learning.* ICLR 2019. [\<arXiv 2018.12\>](https://arxiv.org/abs/1812.05159)
    - *Deep Learning on a Data Diet: Finding Important Examples Early in Training.* [\<NIPS 2021\>](https://proceedings.neurips.cc/paper/2021/hash/ac56f8fe9eea3e4a365f29f0f1957c55-Abstract.html)
    - *Deep Learning Through the Lens of Example Difficulty.* [\<NIPS 2021\>](https://proceedings.neurips.cc/paper/2021/hash/5a4b25aaed25c2ee1b74de72dc03c14e-Abstract.html)
3. **Shapley Value:**
    - *Data Shapley: Equitable Valuation of Data for Machine Learning.* [\<ICML 2019\>](https://proceedings.mlr.press/v97/ghorbani19c.html)
    - *Towards Efficient Data Valuation Based on the Shapley Value.* [\<ICML 2019\>](https://proceedings.mlr.press/v89/jia19a.html)
    - *Data Shapley in One Training Run.* [\<ICLR 2025 Oral\>](https://openreview.net/forum?id=HD6bWcj87Y)
4. **LLM Applications / Techniques:**
    - *Self-Influence Guided Data Reweighting for Language Model Pre-training.* EMNLP 2023.
    - *Entropy-based Adaptive Weighting for Self-Training.*

## Data Selection / Dataset Pruning

1. **Theoretical Studies / Methodology:**
    - *Data Pruning via Moving-one-Sample-out.* Tan. [\<NIPS 2023\>](https://proceedings.neurips.cc/paper_files/paper/2023/hash/3abe23bf7e295b44369c24465d68987a-Abstract-Conference.html) [\<pdf\>](https://proceedings.neurips.cc/paper_files/paper/2023/file/3abe23bf7e295b44369c24465d68987a-Paper-Conference.pdf)
    - *Beyond Neural Scaling Laws: Beating Power Law Scaling via Data Pruning.* [\<NIPS 2023\>](https://proceedings.neurips.cc/paper_files/paper/2022/hash/7b75da9b61eda40fa35453ee5d077df6-Abstract-Conference.html)
    - *Dataset Pruning: Reducing Training Data by Examining Generalization Influence.* [\<ICLR 2023\>](https://openreview.net/forum?id=4wZiAXD29TQ)
2. **LLM Pretraining:**
    - **Notable Survey:**
        - *Findings of the BabyLM Challenge: Sample-Efficient Pretraining on Developmentally Plausible Corpora.* [\<arXiv 2025.4\>](https://arxiv.org/abs/2504.08165)
    - **Difficulty:**
        - *A Little Help Goes a Long Way: Efficient LLM Training by Leveraging Small LMs.* [\<arXiv 2024.10\>](https://arxiv.org/abs/2410.18779)
        - *Data Selection for Language Models via Importance Resampling.* [\<NIPS 2023\>](https://proceedings.neurips.cc/paper_files/paper/2023/hash/6b9aa8f418bde2840d5f4ab7a02f663b-Abstract-Conference.html)
        - *QuRating: Selecting High-Quality Data for Training Language Models.* [\<ICML 2024\>](https://proceedings.mlr.press/v235/wettig24a.html)
        - *Rho-1: Not All Tokens Are What You Need.* [\<NIPS 2024 Oral\>](https://neurips.cc/virtual/2024/poster/96931) [\<arXiv 2024.4\>](https://arxiv.org/abs/2404.07965)
        - *Improving Pretraining Data Using Perplexity Correlations.* [\<ICLR 2025\>](https://openreview.net/forum?id=huuKoVQnB0)
        - *Perplexed by Perplexity: Perplexity-Based Data Pruning With Small Reference Models.* [\<ICLR 2025\>](https://openreview.net/forum?id=1GTARJhxtq)
        - *Dynamic Loss-Based Sample Reweighting for Improved Large Language Model Pretraining.* [\<ICLR 2025\>](https://openreview.net/forum?id=gU4ZgQNsOC)
        - *Adaptive Data Optimization: Dynamic Sample Selection with Scaling Laws.* [\<ICLR 2025\>](https://openreview.net/forum?id=aqok1UX7Z1)
        - *Predictive Data Selection: The Data That Predicts Is the Data That Teaches.* [\<arXiv 2025.3\>](https://arxiv.org/abs/2503.00808)
    - **Diversity:**
        - *D4: Improving LLM Pretraining via Document De-Duplication and Diversification.* [\<NIPS 2023\>](https://proceedings.neurips.cc/paper_files/paper/2023/hash/a8f8cbd7f7a5fb2c837e578c75e5b615-Abstract-Datasets_and_Benchmarks.html)
        - *DoReMi: Optimizing Data Mixtures Speeds Up Language Model Pretraining.* [\<NIPS 2023\>](https://proceedings.neurips.cc/paper_files/paper/2023/hash/dcba6be91359358c2355cd920da3fcbd-Abstract-Conference.html)
            - *ToReMi: Topic-Aware Data Reweighting for Dynamic Pre-Training Data Selection.* [\<arXiv 2025.4\>](https://arxiv.org/abs/2504.00695)
        - *When Less is More: Investigating Data Pruning for Pretraining LLMs at Scale.* [\<NIPS 2023 Workshop\>](https://openreview.net/forum?id=XUIYn3jo5T)
        - *Combatting Dimensional Collapse in LLM Pre-Training Data via Submodular File Selection.* [\<ICLR 2025 Oral\>](https://openreview.net/forum?id=f4gF6AIHRy)
        - *Harnessing Diversity for Important Data Selection in Pretraining Large Language Models.* [\<ICLR 2025 Spotlight\>](https://iclr.cc/virtual/2025/poster/29114) [\<arXiv 2024.9\>](https://arxiv.org/abs/2409.16986)
        - *DataMan: Data Manager for Pre-training Large Language Models.* [\<ICLR 2025\>](https://openreview.net/forum?id=eNbA8Fqir4)
        - *Enhancing Multilingual LLM Pretraining with Model-Based Data Selection.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.10361)
        - *Data Differences over Scale (DataDos) Suite: How to Predict Best Pretraining Data with Small Experiments.* [\<ICML 2025\>](https://icml.cc/virtual/2025/poster/44022)
3. **LLM Fine-tuning / Alignment:**
    - *LESS: Selecting Influential Data for Targeted Instruction Tuning.* [\<ICML 2024 Workshop\>](https://iclr.cc/virtual/2024/22436)
    - *Improving Data Efficiency via Curating LLM-Driven Rating Systems.* [\<ICLR 2025\>](https://iclr.cc/virtual/2025/poster/30465) [\<arXiv 2024.10\>](https://arxiv.org/abs/2410.10877)
    - *Do We Really Have to Filter Out Random Noise in Pre-training Data for Language Models?* [\<ACL ARR 2024\>](https://openreview.net/forum?id=1xf3oyu5Ac)
    - *Principled Data Selection for Alignment: The Hidden Risks of Difficult Examples.* ICML 2025.
    - *The Best Instruction-Tuning Data are Those That Fit.* [\<arXiv 2025.2\>](https://arxiv.org/abs/2502.04194)
    - *RedStar: Does Scaling Long-CoT Data Unlock Better Slow-Reasoning Systems?* [\<arXiv 2025.1\>](https://arxiv.org/abs/2501.11284)
    - *Large-Scale Data Selection for Instruction Tuning.* [\<arXiv 2025.3\>](https://arxiv.org/abs/2503.01807)
    - *Reverse Modeling in Large Language Models.* [\<arXiv 2024.10\>](https://arxiv.org/abs/2410.09817)
4. **LLM Reinforcement Learning / Reasoning:**
    - *Entropy-guided Sequence Weighting for Efficient Exploration in RL-based LLM Fine-tuning.*
    - *TwT: Thinking without Tokens by Habitual Reasoning Distillation with Multi-Teachers' Guidance.* [\<arXiv 2025.3\>](https://arxiv.org/abs/2503.24198)
    - *ThinkPrune: Pruning Long Chain-of-Thought of LLMs via Reinforcement Learning.* [\<arXiv 2025.4\>](https://arxiv.org/abs/2504.01296)
    - *Efficient Reinforcement Finetuning via Adaptive Curriculum Learning.* [\<arXiv 2025.4\>](https://arxiv.org/abs/2504.05520)
    - *How Instruction and Reasoning Data Shape Post-Training: Data Quality through the Lens of Layer-wise Gradients.* [\<arXiv 2025.4\>](https://arxiv.org/abs/2504.10766v1)
    - *Rethinking the Generation of High-Quality CoT Data from the Perspective of LLM-Adaptive Question Difficulty Grading.* [\<arXiv 2025.4\>](https://arxiv.org/abs/2504.11919)
    - *AdaSTaR: Adaptive Data Sampling for Training Self-Taught Reasoners.* [\<arXiv 2025.5\>](https://arxiv.org/abs/2505.16322v1)
5. **Online Data Selection:**
    - *Accelerating Deep Learning with Dynamic Data Pruning.* [\<arXiv 2021.11\>](https://arxiv.org/abs/2111.12621)
    - *Learned Token Pruning for Transformers.* [\<arXiv 2021.7\>](https://arxiv.org/abs/2107.00910)
    - *InfoBatch: Lossless Training Speed Up by Unbiased Dynamic Data Pruning.* [\<ICLR 2024\>](https://openreview.net/forum?id=C61sk5LsK6)
    - *GREATS: Online Selection of High-Quality Data for LLM Training in Every Iteration.* [\<NIPS 2024 Spotlight\>](https://openreview.net/forum?id=232VcN8tSx)

## Synthetic Data / Dataset Distillation

1. **CNN / Diffusion:**
    - *Dataset Distillation.* [\<arXiv 2018\>](https://arxiv.org/abs/1811.10959)
    - *Dataset Condensation with Gradient Matching.* [\<ICLR 2021 Oral\>](https://openreview.net/forum?id=mSAKhLYLSsl)
    - *Squeeze, Recover and Relabel: Dataset Condensation at ImageNet Scale from a New Perspective.* [\<NIPS 2023\>](https://proceedings.neurips.cc/paper_files/paper/2023/hash/e91fb65c6324a984ea9ef39a5b84af04-Abstract-Conference.html)
    - *Dataset Diffusion: Diffusion-based Synthetic Data Generation for Pixel-Level Semantic Segmentation.* [\<NIPS 2023\>](https://proceedings.neurips.cc/paper_files/paper/2023/hash/f2957e48240c1d90e62b303574871b47-Abstract-Conference.html)
    - *Elucidating the Design Space of Dataset Condensation.* NIPS 2024. [\<arXiv 2024.4\>](https://arxiv.org/abs/2404.13733)
    - *Distilling Dataset into Neural Field.*
2. **Transformer / LLM:**
    - *Farzi Data: Autoregressive Data Distillation.* [\<arXiv 2023.10\>](https://arxiv.org/abs/2310.09983) [\<ICLR 2024 Reject\>](https://openreview.net/forum?id=H9DYMIpz9c)
    - *DataDreamer: A Tool for Synthetic Data Generation and Reproducible LLM Workflows.* [\<arXiv 2024.2\>](https://arxiv.org/abs/2402.10379)
    - *Best Practices and Lessons Learned on Synthetic Data.* [\<arXiv 2024.4\>](https://arxiv.org/abs/2404.07503)
    - *The Parrot Dilemma: Human-Labeled vs. LLM-augmented Data in Classification Tasks.* [\<EACL 2024\>](https://aclanthology.org/2024.eacl-short.17/)
    - *Large Language Models for Data Annotation and Synthesis: A Survey.* [\<EMNLP 2024\>](https://aclanthology.org/2024.emnlp-main.54/)
    - *Towards a Theoretical Understanding of Synthetic Data in LLM Post-Training: A Reverse-Bottleneck Perspective.* [\<ICLR 2025\>](https://iclr.cc/virtual/2025/poster/29438) [\<arXiv\>](https://arxiv.org/abs/2410.01720)
    - *Fictitious Synthetic Data Can Improve LLM Factuality via Prerequisite Learning.* [\<ICLR 2025\>](https://iclr.cc/virtual/2025/poster/29436) [\<arXiv\>](https://arxiv.org/abs/2410.19290)
    - *DataGen: Unified Synthetic Dataset Generation via Large Language Models.* [\<ICLR 2025\>](https://iclr.cc/virtual/2025/poster/30365)
    - *Synthetic Continued Pretraining.* [\<ICLR 2025 Oral\>](https://iclr.cc/virtual/2025/poster/31270)
    - *Synthetic Data Generation & Multi-Step RL for Reasoning & Tool Use.* [\<arXiv 2025.4\>](https://arxiv.org/abs/2504.04736)
    - *Mining Hidden Thoughts from Texts: Evaluating Continual Pretraining with Synthetic Data for LLM Reasoning.*
    - *FLAMES: Improving LLM Math Reasoning via a Fine-Grained Analysis of the Data Synthesis Pipeline.* [\<EMNLP 2025\>](https://arxiv.org/abs/2508.16514v1)
    - *DESIGNER: Design-Logic-Guided Multidisciplinary Data Synthesis for LLM Reasoning.* [\<arXiv 2025.8\>](https://arxiv.org/abs/2508.12726v1)
3. **MultiModal / VLLM:**
    - *StableLLaVA: Enhanced Visual Instruction Tuning with Synthesized Image-Dialogue Data.* [\<arXiv 2023.8\>](https://arxiv.org/abs/2308.10253)
    - *LOKI: A Comprehensive Synthetic Data Detection Benchmark using Large Multimodal Models.* [\<ICLR 2025\>](https://iclr.cc/virtual/2025/poster/27689)
    - *Unicorn: Text-Only Data Synthesis for Vision Language Model Training.*
    - *Token Sequence Compression for Efficient Multimodal Computing.* arXiv 2025.4.
