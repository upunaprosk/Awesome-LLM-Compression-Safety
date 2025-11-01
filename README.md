# Compression Side Effects [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Quantization and other model compression techniques significantly improve efficiency, but may also compromise trustworthiness, fairness, and overall model reliability.

This repository provides a **curated list of papers, benchmarks, and resources** exploring the *undesired side effects* of model compression — particularly focusing on its impact on: **Fairness**, **Robustness**, **Calibration**,  **Toxicity and Safety**.

<p align="center">
  <img src="https://github.com/upunaprosk/Awesome-Compression-Safety/blob/master/figure-Page-2.png" alt="Compression Side Effects" width="400">
</p>



## Paper List - Compression Side Effects

### Fairness: Monolingual and Multilingual
- **Fair-GPTQ: Bias-Aware Quantization for Large Language Models** (Proskurina et al., 2025) – [arXiv](https://arxiv.org/abs/2509.15206)
- **Can Model Compression Improve NLP Fairness** (Xu & Hu, 2022) – [arXiv](https://arxiv.org/abs/2201.08542)
- **A Comparative Study on the Impact of Model Compression Techniques on Fairness in Language Models** (Ramesh et al., 2023) – [ACL Anthology](https://aclanthology.org/2023.acl-long.878/)
- **The Impact of Model Compression on Fairness** (Kamal, 2024) – [FLAIRS PDF](https://journals.flvc.org/FLAIRS/article/download/135617/140005/260572)
- **You Never Know: Quantization Induces Inconsistent Biases in Vision-Language Foundation Models** (Slyman et al., 2024) – [arXiv](https://arxiv.org/abs/2410.20265)
- **How Does Quantization Affect Multilingual LLMs?** (Li et al., 2024) – [ACL Anthology](https://aclanthology.org/2024.findings-emnlp.935/)
- **Decoding Compressed Trust: Scrutinizing the Trustworthiness of Efficient LLMs Under Compression** (Hong et al., 2024, ICML) – [arXiv](https://arxiv.org/abs/2403.15447)
- **Beyond Perplexity: Multi-dimensional Safety Evaluation of LLM Compression** (Xu et al., 2024, EMNLP Findings) – [ACL Anthology](https://aclanthology.org/2024.findings-emnlp.901/)
- **Understanding the Unfairness in Network Quantization** (Zhang et al., 2025, ICML) – [Poster](https://icml.cc/virtual/2025/poster/43689)
- **Downsized and Compromised?: Assessing the Faithfulness of Model Compression** (Kamal & Talbert, 2025) – [arXiv](https://arxiv.org/abs/2510.06125)
- **The Effect of Model Compression on Fairness in Facial Expression Recognition** (Stoychev & Gunes, 2022) – [arXiv](https://arxiv.org/abs/2201.01709)

---

### Robustness
- **Benchmarking Post-Training Quantization in LLMs: A Comprehensive Taxonomy** (Zhou et al., 2025) – [arXiv](https://arxiv.org/abs/2502.13178)
- **A Comprehensive Evaluation of Quantization Strategies for Large Language Models** (Smith et al., 2024) – [ACL Anthology](https://aclanthology.org/2024.findings-acl.726/)
- **BiLLM: Pushing the Limit of Post-Training Quantization for LLMs** (Liu et al., 2024) – [arXiv](https://arxiv.org/abs/2402.04291)
- **Exploiting LLM Quantization** (Egashira et al., 2024, NeurIPS) – [PDF](https://proceedings.neurips.cc/paper_files/paper/2024/file/496720b3c860111b95ac8634349dcc88-Paper-Conference.pdf)
- **A Comprehensive Review of Model Compression Techniques in Machine Learning** (Dantas et al., 2024) – [SpringerLink](https://link.springer.com/article/10.1007/s10489-024-05747-w)
- **Compression Scaling Laws: Unifying Sparsity and Quantization** (Zhang et al., 2025) – [arXiv](https://arxiv.org/html/2502.16440v1)
- **Towards Understanding Model Quantization for Reliable Deep Neural Network Deployment** (Hu et al., 2023) – [PDF](https://orbilu.uni.lu/bitstream/10993/59236/1/CAIN2023_quantization%20%281%29.pdf)
- **Model Compression in Practice: Lessons Learned from Real Deployments** (2024) – [ACM DL](https://dl.acm.org/doi/10.1145/3613904.3642109)

---

### Calibration Error & Confidence & Calibration Data
- **When Quantization Affects Confidence of Large Language Models?** (Proskurina et al., 2024, NAACL) – [ACL Anthology](https://aclanthology.org/2024.findings-naacl.124/)
- **An Underexplored Dilemma between Confidence and Calibration in Quantized Neural Networks** (Xia et al., 2021) – [arXiv](https://arxiv.org/abs/2111.08163)
- **On the Impact of Calibration Data in Post-Training Quantization and Pruning** (Williams & Aletras, 2024) – [ACL Anthology](https://aclanthology.org/2024.acl-long.544/)
- **Self-Calibration for Language Model Quantization and Pruning** (Li et al., 2025) – [arXiv](https://arxiv.org/abs/2410.17170)
- **Preserving LLM Capabilities through Calibration Data Curation: From Analysis to Optimization** (He et al., 2025, Neurips) – [arXiv](https://arxiv.org/abs/2510.10618)
- **Beware of Calibration Data for Pruning Large Language Models** (Ji et al., 2025, ICLR) – [OpenReview](https://openreview.net/forum?id=x83w6yGIWb)
- **PD-Quant: Post-Training Quantization Based on Prediction Difference Metric** (Liu et al., 2022, IEEE/CVF) – [arXiv](https://arxiv.org/abs/2212.07048)
- **Interpreting the Effects of Quantization on LLMs** (Singh et al., 2025) – [arXiv](https://arxiv.org/pdf/2508.16785)

---

### Toxicity & Safety
- **Beyond Perplexity: Multi-dimensional Safety Evaluation of LLM Compression** (Xu et al., 2024) – [ACL Anthology](https://aclanthology.org/2024.findings-emnlp.901/)
- **Decoding Compressed Trust: Scrutinizing the Trustworthiness of Efficient LLMs Under Compression** (Hong et al., 2024, ICML) – [arXiv](https://arxiv.org/abs/2403.15447)
- **Assessing Safety Risks and Quantization-Aware Safety-Patching Framework (Q-Resafe)** (Patel et al., 2025, ICML) – [Poster](https://icml.cc/virtual/2025/poster/44278)
- **HarmLevelBench: Evaluating Harm-Level Compliance and the Impact of Quantization on Model Alignment** (Belkhiter, Zizzo, Maffeis; 2024) – [arXiv](https://arxiv.org/abs/2411.06835)

