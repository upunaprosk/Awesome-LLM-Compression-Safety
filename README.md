<div align="center">

<img src="banner_image.png" width="80%">
</div>

<div align="center">
    <h1>Awesome LLM Compression Safety</h1>
    <a href="https://awesome.re"><img src="https://awesome.re/badge.svg"/></a>
    <p align="center">
        <a href="#"><img src="https://img.shields.io/github/stars/upunaprosk/Awesome-LLM-Compression-Safety?style=flat-square&logo=github" alt="GitHub stars"></a>
        <a href="#"><img src="https://img.shields.io/github/forks/upunaprosk/Awesome-LLM-Compression-Safety?style=flat-square&logo=github" alt="GitHub forks"></a>
        <a href="#"><img src="https://img.shields.io/github/issues/upunaprosk/Awesome-LLM-Compression-Safety?style=flat-square&logo=github" alt="GitHub issues"></a>
        <a href="#"><img src="https://img.shields.io/github/last-commit/upunaprosk/Awesome-LLM-Compression-Safety?style=flat-square&logo=github" alt="GitHub last commit"></a>
    </p>
</div>

---

## 🤗 Introduction

Model compression techniques, such as quantization, pruning, distillation, and low-rank adaptation, are widely used to reduce the deployment cost of language models while maintaining performance. However, compression can result in:

- Increased stereotype generation  
- Reduced robustness to adversarial attacks  
- Increased calibration errors
- Higher model uncertainty 
- Overall safety risks in downstream applications  

**This repository curates papers on the evaluation and mitigation of compression-induced safety degradation in LLMs, VLMs, and multimodal models**, covering robustness, calibration, and alignment.

> Papers are currently listed in a single section. Subcategories will be introduced as the collection grows.

**Contributions are welcome!** Please open an issue or submit a pull request following the existing format.

---

## Table of Contents

- [📑 Papers](#-papers)
- [Benchmarks](#benchmarks)

---

## 📑 Papers

| Date  | Institute | Venue | Paper |
|:-----:|:---------:|:-----------:|:-----:|
| 20.10 | Google Research | arXiv | [Characterising Bias in Compressed Models](https://arxiv.org/abs/2010.03058) |
| 22.01 | University of California | arXiv | [Can Model Compression Improve NLP Fairness](https://arxiv.org/abs/2201.08542) |
| 22.01 | University of Cambridge | ICPR 2022 | [The Effect of Model Compression on Fairness in Facial Expression Recognition](https://arxiv.org/abs/2201.01709) |
| 22.12 | NAVER LABS Europe; IDIAP Research Institute; EPFL | EMNLP 2022 | [What Do Compressed Multilingual Machine Translation Models Forget?](https://aclanthology.org/2022.findings-emnlp.317/) |
| 23.05 | NJIT; Microsoft Research; Rice University | EACL 2023 | [Robustness Challenges in Model Distillation and Pruning for Natural Language Understanding](https://aclanthology.org/2023.eacl-main.129/) |
| 23.07 | Microsoft Research; IIT Dhanbad; BITS Pilani | ACL 2023 | [A Comparative Study on the Impact of Model Compression Techniques on Fairness in Language](https://aclanthology.org/2023.acl-long.878) |
| 23.10 | UT Austin; Apple | ICLR 2024 | [Compressing LLMs: The Truth Is Rarely Pure and Never Simple](https://arxiv.org/abs/2310.01382) |
| 23.12 | Carnegie Mellon University; Universidade NOVA de Lisboa; Allen Institute for AI | EMNLP 2023 | [Understanding the Effect of Model Compression on Social Bias in Large Language Models](https://aclanthology.org/2023.emnlp-main.161/) |
| 23.12 | Cohere For AI; Dyania Health; University of Virginia | ICML 2024 | [On the Fairness Impacts of Hardware Selection in Machine Learning](https://arxiv.org/abs/2312.03886) |
| 24.01 | MIT | BlackboxNLP Workshop (ACL 2024) | [Pruning for Protection: Increasing Jailbreak Resistance in Aligned LLMs Without Fine-Tuning](https://arxiv.org/abs/2401.10862) |
| 24.02 | Princeton University | ICML 2024 | [Assessing the Brittleness of Safety Alignment via Pruning and Low-Rank Modifications](https://arxiv.org/abs/2402.05162) |
| 24.03 | UT Austin; Drexel; MIT; UIUC; Duke; LLNL; CAIS; UC Berkeley; UChicago | ICML 2024 | [Decoding Compressed Trust: Scrutinizing the Trustworthiness of Efficient LLMs Under Compression](https://arxiv.org/abs/2403.15447) |
| 24.05 | Tennessee Tech University | FLAIRS 2024 | [Beyond Size and Accuracy: The Impact of Model Compression on Fairness](https://journals.flvc.org/FLAIRS/article/view/135792) |
| 24.05 | ETH Zurich | NeurIPS 2024 | [Exploiting LLM Quantization](https://arxiv.org/abs/2405.18137) |
| 24.06 | Université Lumière Lyon 2; Université Claude Bernard Lyon 1 | NAACL 2024 | [When Quantization Affects Confidence of Large Language Models?](https://aclanthology.org/2024.findings-naacl.124/) |
| 24.06 | Penn State; NEC Labs America | NAACL 2024 | [Pruning as a Domain-Specific LLM Extractor](https://aclanthology.org/2024.findings-naacl.91/) |
| 24.10 | The Pennsylvania State University; Harvard University; Amazon | ICLR 2025 | [Catastrophic Failure of LLM Unlearning via Quantization](https://arxiv.org/abs/2410.16454) |
| 24.10 | Oregon State University | NeurIPS 2024 (RBFM) | [You Never Know: Quantization Induces Inconsistent Biases in Vision-Language Foundation Models](https://arxiv.org/abs/2410.20265) |
| 24.11 | MIT | BlackboxNLP @ EMNLP 2024 | [Pruning for Protection: Increasing Jailbreak Resistance in Aligned LLMs Without Fine-Tuning](https://aclanthology.org/2024.blackboxnlp-1.26) |
| 24.11 | University of Utah; Google DeepMind | EMNLP 2024 | [Beyond Perplexity: Multi-dimensional Safety Evaluation of LLM Compression](https://aclanthology.org/2024.findings-emnlp.901/) |
| 24.11 | Cohere; Cohere For AI | EMNLP 2024 | [How Does Quantization Affect Multilingual LLMs?](https://aclanthology.org/2024.findings-emnlp.935/) |
| 24.12 | ETH Zurich | Conference | [Exploiting LLM Quantization](https://openreview.net/pdf?id=496720b3c860111b95ac8634349dcc88) |
| 25.01 | CISPA Helmholtz Center for Information Security; Peking University | ICLR 2025 | [SaLoRA: Safety-Alignment Preserved Low-Rank Adaptation](https://arxiv.org/abs/2501.01765) |
| 25.02 | Zhejiang University; University of Waterloo; Sun Yat-sen University | USENIX Security 2025 | [Activation Approximations Can Incur Safety Vulnerabilities Even in Aligned LLMs: Comprehensive Analysis and Defense](https://arxiv.org/abs/2502.00840) |
| 25.04 | The Hong Kong University of Science and Technology | ICLR 2025 | [Durable Quantization Conditioned Misalignment Attack on Large Language Models](https://proceedings.iclr.cc/paper_files/paper/2025/hash/376b1b131609e764f687afca832e62b3-Abstract-Conference.html) |
| 25.05 | University of Calgary; Vector Institute | ICML 2025 | [Does Compression Exacerbate Large Language Models' Social Bias?](https://openreview.net/pdf?id=iFFfAbFp8a) |
| 25.05 | Ruhr University Bochum; UAR Research Center | NAACL 2025 | [The Impact of Inference Acceleration on Bias of LLMs](https://aclanthology.org/2025.naacl-long.91) |
| 25.05 | East China Normal University | ACL 2025 Findings | [Hierarchical Safety Realignment: Lightweight Restoration of Safety in Pruned Large Vision-Language Models](https://arxiv.org/abs/2505.16104) |
| 25.06 | Zhejiang University; Hangzhou High-Tech Zone (Binjiang) Institute of Blockchain and Data Security; Sun Yat-sen University | ICML 2025 | [Q-resafe: Assessing Safety Risks and Quantization-aware Safety Patching for Quantized Large Language Models](https://arxiv.org/abs/2506.20251) |
| 25.06 | University of Southampton; University of Liverpool | TACL 2025 | [Safe Pruning LoRA: Robust Distance-Guided Pruning for Safety Alignment in Adaptation of LLMs](https://aclanthology.org/2025.tacl-1.67/) |
| 25.06 | University of São Paulo | COLM 2025 | [LoX: Low-Rank Extrapolation Robustifies LLM Safety Against Fine-tuning](https://arxiv.org/abs/2506.15606) 
| 25.06 | Tsinghua University | EMNLP 2025 | [The Security Threat of Compressed Projectors in Large Vision-Language Models](https://arxiv.org/abs/2506.00534) |
| 25.07 | Red Hat AI; IST Austria | ACL 2025 | ["Give Me BF16 or Give Me Death"? Accuracy-Performance Trade-offs in LLM Quantization](https://aclanthology.org/2025.acl-long.1304/) |
| 25.07 | Tongji University; University of Electronic Science and Technology of China | NeurIPS 2025 | [SafePTR: Token-Level Jailbreak Defense in Multimodal LLMs via Prune-then-Restore Mechanism](https://arxiv.org/abs/2507.01513) |
| 25.08 | Sofia University; Tsinghua University; Hebrew University; TU Darmstadt; ATHENE | EACL 2026 | [How Quantization Shapes Bias in Large Language Models](https://arxiv.org/abs/2508.18088) |
| 25.08 | Dalhousie University | AACL 2025 | [Interpreting the Effects of Quantization on LLMs](https://arxiv.org/abs/2508.16785) |
| 25.09 | Université Lumière Lyon 2; Université Claude Bernard Lyon 1; École Centrale de Lyon; LIRIS CNRS | arXiv | [Fair-GPTQ: Bias-Aware Quantization for Large Language Models](https://arxiv.org/abs/2509.15206) |
| 25.10 | Tennessee Tech University | arXiv | [Downsized and Compromised? Assessing the Faithfulness of Model Compression](https://arxiv.org/abs/2510.06125) |
| 25.10 | University of Hong Kong; Huawei | NeurIPS 2025 | [Preserving LLM Capabilities through Calibration Data Curation](https://arxiv.org/abs/2510.10618) |
| 25.10 | ETH Zurich | arXiv | [Fewer Weights, More Problems: A Practical Attack on LLM Pruning](https://arxiv.org/abs/2510.07985) |
| 25.11 | UMass Amherst; Microsoft; University of Maryland | EMNLP 2025 | [Does Quantization Affect Models’ Performance on Long-Context Tasks?](https://aclanthology.org/2025.emnlp-main.479/) |
| 25.11 | Iowa State University | arXiv | [Decomposed Trust: Exploring Privacy, Adversarial Robustness, Fairness, and Ethics of Low-Rank LLMs](https://arxiv.org/abs/2511.22099) |
| 25.11 | Seoul National University | arXiv | [Alignment-Aware Quantization for LLM Safety](https://arxiv.org/abs/2511.07842) |
| 25.11 | GE HealthCare | NeurIPS 2025 (Lock-LLM Workshop) | [Compressed but Compromised? A Study of Jailbreaking in Compressed LLMs](https://openreview.net/pdf?id=OkNfb8SmLh) |
| 25.11 | ALMAnaCH Inria Paris, France | TACL 2025 | [Benchmarking Linguistic Diversity of Large Language Models](https://aclanthology.org/2025.tacl-1.69/) |
| 25.12 | Huazhong University of Science and Technology | ICML 2025 | [Understanding the Unfairness in Network Quantization](https://icml.cc/virtual/2025/poster/43689) |
| 26.01 | Universitas Indonesia | arXiv | [Preserving Fairness and Safety in Quantized LLMs Through Critical Weight Protection](https://arxiv.org/abs/2601.12033) |
| 26.01 | University of Georgia; University of North Texas; Hong Kong Polytechnic University; Northeastern University | arXiv | [Q-realign: Piggybacking Realignment on Quantization for Safe and Efficient LLM Deployment](https://arxiv.org/abs/2601.08089) |
| 26.02 | University College London; University of Tübingen | arXiv | [UniComp: A Unified Evaluation of Large Language Model Compression](https://arxiv.org/abs/2602.09130) |
| 26.02 | UC Berkeley; Meta Superintelligence Labs | COLM 2026 | [Investigating Social Bias Changes in Quantized Language Models](https://arxiv.org/abs/2602.06181) |
| 26.03 | Shanghai University | TACL 2026 | [Safety-Potential Pruning for Enhancing Safety Prompts Against VLM Jailbreaking Without Retraining](https://arxiv.org/abs/2603.14219) |
| 26.04 | Mohamed bin Zayed University of Artificial Intelligence | arXiv | [Shorter, but Still Trustworthy? An Empirical Study of Chain-of-Thought Compression](https://arxiv.org/abs/2604.04120) |
| 26.04 | Zhejiang University; National University of Singapore | WWW 2026 | [LLMQuA: Practical Backdoor Injection on Large Language Model Quantization](https://dl.acm.org/doi/10.1145/3774904.3792256) |
| 26.05 | ETH Zurich | arXiv | [Widening the Gap: Exploiting LLM Quantization via Outlier Injection](https://arxiv.org/abs/2605.15152) |
| 26.05 | Meta | IEEE Cloud Summit 2026 | [Quantization Undoes Alignment: Bias Emergence in Compressed LLMs Across Models and Precision Levels](https://arxiv.org/abs/2605.15208) |
| 26.06 | Stanford University; California Institute of Technology | arXiv | [Alignment Collapse Under KV Cache Quantization: Diagnosis and Mitigation](https://arxiv.org/abs/2606.09864) |
| 26.06 | University of Luebeck | arXiv | [FloatDoor: Platform-Triggered Backdoors in LLMs](https://arxiv.org/abs/2606.19535) |
| 26.06 | Shandong University | ACM CCS 2026 | [Breaking the Rounding Trap: Securing LLMs against Quantization-Conditioned Backdoors](https://arxiv.org/abs/2606.29239) |
| 26.09 | Jean Monnet University | EMNLP 2026 | [Debias-SparseGPT: Bias-Aware Pruning for Large Language Models](https://arxiv.org/abs/2609.02496) |


---

## Benchmarks

| Date  | Institute | Publication | Paper |
|:-----:|:---------:|:-----------:|:-----:|
| 24.03 | UT Austin; Drexel; MIT; UIUC; Duke; LLNL; CAIS; UC Berkeley; UChicago | ICML 2024 | [Decoding Compressed Trust: Scrutinizing the Trustworthiness of Efficient LLMs Under Compression](https://arxiv.org/abs/2403.15447) |
| 24.10 | Beihang University; ETH Zurich; Carnegie Mellon University | NeurIPS 2024 Datasets and Benchmarks Track | [LLMCBench: Benchmarking Large Language Model Compression for Efficient Deployment](https://arxiv.org/abs/2410.21352) |
| 24.12 | IBM Research Europe; Trinity College Dublin; Imperial College London | NeurIPS 2024 SafeGenAI | [HarmLevelBench: Evaluating Harm-Level Compliance and the Impact of Quantization on Model Alignment](https://arxiv.org/abs/2411.06835) |
| 25.02 | Skolkovo Institute of Science and Technology; AIRI; HSE University | arXiv | [Investigating the Impact of Quantization Methods on the Safety and Reliability of Large Language Models](https://arxiv.org/abs/2502.15799) |
| 25.02 | Harbin Institute of Technology (Shenzhen); Illinois Institute of Technology | arXiv | [Benchmarking Post-Training Quantization in LLMs: A Comprehensive Taxonomy](https://arxiv.org/abs/2502.13178) |

## Cite

If you use this repository in your research, you can cite it as:

```bibtex
@misc{proskurina2026awesome_llm_compression_safety,
  title        = {Awesome LLM Compression Safety},
  author       = {Proskurina, Irina},
  year         = {2026},
  howpublished = {\url{https://github.com/upunaprosk/Awesome-LLM-Compression-Safety}},
  note         = {GitHub repository, accessed 2026}
}
```
