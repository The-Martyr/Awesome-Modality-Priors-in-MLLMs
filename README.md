# Awesome-Modality-Priors-in-MLLMs [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This is a repository for organizing papres related to modality priors of Multimodal Large Language Models (MLLM).

Modality priors in multimodal large language models (MLLMs) include visual priors, language priors, etc., which refer to inherent biases or preconceptions embedded in components such as the visual encoder and language model of MLLMs. These priors come from the text data on which visual pre-training and language model training are based, and affect how the model combines other modalities to interpret and generate language. They affect the model's predictions, leading to potential biases or expectations about the relationship between different types of data in a multimodal context.

#### :star: If you find this list useful, welcome to star it!

## Paper List (Updating...)

### Mitigation

(16 Apr 2025) [Efficient Contrastive Decoding with Probabilistic Hallucination Detection - Mitigating Hallucinations in Large Vision Language Models](https://arxiv.org/abs/2504.12137v1) 

(17 Oct 2024) [Mitigating Hallucinations in Large Vision-Language Models via Summary-Guided Decoding](https://arxiv.org/abs/2410.13321)

(7 Oct 2024) [Mitigating Modality Prior-Induced Hallucinations in Multimodal Large Language Models via Deciphering Attention Causality](https://arxiv.org/abs/2410.04780)

(31 Jul 2024) [Paying More Attention to Image: A Training-Free Method for Alleviating Hallucination in LVLMs](https://arxiv.org/abs/2407.21771)

(24 Jun 2024) [Cambrian-1: A Fully Open, Vision-Centric Exploration of Multimodal LLMs](https://arxiv.org/abs/2406.16860)

(19 Jun 2024) [VACoDe: Visual Augmented Contrastive Decoding](https://openreview.net/forum?id=Li4mQaI1H4)

(17 Jun 2024) [mDPO: Conditional Preference Optimization for Multimodal Large Language Models](https://arxiv.org/abs/2406.11839)

(6 Apr 2024) [Context versus Prior Knowledge in Language Models](https://arxiv.org/abs/2404.04633)

(27 Mar 2024) [Mitigating Hallucinations in Large Vision-Language Models with Instruction Contrastive Decoding](https://arxiv.org/abs/2403.18715)

(8 Mar 2024) [Debiasing Multimodal Large Language Models](https://arxiv.org/abs/2403.05262)

(28 Nov 2023) [Mitigating Object Hallucinations in Large Vision-Language Models through Visual Contrastive Decoding](https://arxiv.org/abs/2311.16922)

(26 Jun 2023) [Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning](https://arxiv.org/abs/2306.14565)

(31 May 2023) [Unveiling Cross Modality Bias in Visual Question Answering: A Causal View with Possible Worlds VQA](https://arxiv.org/abs/2305.19664)

### Benchmark & Dataset

(4 May 2025) [A Comprehensive Analysis for Visual Object Hallucination in Large Vision-Language Models](https://arxiv.org/abs/2505.01958v1) 

(17 Feb 2025) [LanP: Rethinking the Impact of Language Priors in Large Vision-Language Models](https://arxiv.org/abs/2502.12359)

(31 Dec 2024) [Probing Visual Language Priors in VLMs](https://www.arxiv.org/abs/2501.00569)

(13 Jun 2024) [VLind-Bench: Measuring Language Priors in Large Vision-Language Models](https://arxiv.org/abs/2406.08702)

(23 May 2023) [IfQA: A Dataset for Open-domain Question Answering under Counterfactual Presuppositions](https://arxiv.org/abs/2305.14010)

(13 Mar 2023) [Breaking Common Sense: WHOOPS! A Vision-and-Language Benchmark of Synthetic and Compositional Images](https://arxiv.org/abs/2303.07274)

(30 Oct 2023) [ROME: Evaluating Pre-trained Vision-Language Models on Reasoning beyond Visual Common Sense](https://arxiv.org/abs/2310.19301)

### Evaluation

(18 Apr 2025) [The Mirage of Performance Gains: Why Contrastive Decoding Fails to Address Multimodal Hallucination](https://arxiv.org/abs/2504.10020v2)

(4 Mar 2025) [Words or Vision: Do Vision-Language Models Have Blind Faith in Text?](https://arxiv.org/abs/2503.02199)

(16 Oct 2024) [The Curse of Multi-Modalities: Evaluating Hallucinations of Large Multimodal Models across Language, Visual, and Audio](https://arxiv.org/abs/2410.12787)

(30 Sep 2024) [Do Vision-Language Models Really Understand Visual Language?](https://arxiv.org/abs/2410.00193)

(5 Jul 2023) [Reasoning or Reciting? Exploring the Capabilities and Limitations of Language Models Through Counterfactual Tasks](https://arxiv.org/abs/2307.02477)

### Related Works

(4 Jun 2024) [Eliciting the Priors of Large Language Models using Iterated In-Context Learning](https://arxiv.org/abs/2406.01860)

(25 Mar 2024) [The Strong Pull of Prior Knowledge in Large Language Models and Its Impact on Emotion Recognition](https://arxiv.org/abs/2403.17125)

(11 August 2023) [Robust visual question answering via polarity enhancement and contrast](https://www.sciencedirect.com/science/article/pii/S0893608024004842)

(1 Dec 2017) [Don't Just Assume; Look and Answer: Overcoming Priors for Visual Question Answering](https://arxiv.org/abs/1712.00377)

### First Paper of Language Priors in Multimodality

(CVPR 2016) [Yin and Yang: Balancing and Answering Binary Visual Questions](https://arxiv.org/abs/1511.05099)

### Previous Study in VQA

(CVPR 2017) Making the V in VQA Matter: Elevating the Role of Image Understanding in Visual Question Answering

(CVPR 2018) Don’t Just Assume; Look and Answer: Overcoming Priors for Visual Question Answering

(NIPS 2018) Overcoming Language Priors in Visual Question Answering with Adversarial Regularization

(SIGIR 2019) Quantifying and Alleviating the Language Prior Problem in Visual Question Answering

(CVPR 2021) Counterfactual VQA: A Cause-Effect Look at Language Bias

(TIP 2021) Loss Re-Scaling VQA: Revisiting the Language Prior Problem From a Class-Imbalance View

(EMNLP 2022) Language Prior Is Not the Only Shortcut: A Benchmark for Shortcut Learning in VQA

(COLING 2022) Overcoming Language Priors in Visual Question Answering via Distinguishing Superficially Similar Instances

(JMLR 2023) Overcoming Language Priors for Visual Question Answering via Loss Rebalancing Label and Global Context
