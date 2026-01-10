<div align="center">
    <h1>Awesome Compression Safety</h1>
    <a href="https://awesome.re"><img src="https://awesome.re/badge.svg"/></a>
</div>

**What breaks when we compress large language models?**

A curated list of research studying **undesired effects of model compression** in LLMs, VLMs, and multimodal models, with a focus on fairness, robustness, calibration, and safety.  
Contributions are welcome!


<p align="center">
  <img src="llm_compression_safety.gif" alt="LLM Compression Safety" width="700">
</p>

---

## 🆕 Recent Papers (2025)

- Fair-GPTQ: Bias-Aware Quantization for Large Language Models (2025)
- Understanding the Unfairness in Network Quantization (ICML 2025)
- Decomposed Trust: Exploring Privacy, Adversarial Robustness, Fairness, and Ethics of Low-Rank LLMs (2025)
- Compressed but Compromised? Jailbreaking in Compressed LLMs (2025)

---

## Surveys

- **A Comprehensive Review of Model Compression Techniques in Machine Learning**  
  Dantas et al., 2024  
  https://link.springer.com/article/10.1007/s10489-024-05747-w

- **A Review of State-of-the-Art Techniques for Large Language Model Compression**  
  Dantas et al., 2025  
  https://link.springer.com/article/10.1007/s40747-025-02019-z

---

## Scope

This list focuses on how compression methods (quantization, pruning, distillation, low-rank methods) affect:

- fairness and bias
- robustness and reliability
- calibration and confidence
- toxicity, alignment, and safety
- faithfulness and trustworthiness

Papers that focus only on efficiency or aggregate accuracy, without analyzing behavioral, fairness, robustness, or safety effects, are out of scope.

---

## Contents

- [Fairness & Bias](#fairness--bias)
- [Robustness & Reliability](#robustness--reliability)
- [Calibration & Confidence](#calibration--confidence)
- [Toxicity & Safety](#toxicity--safety)
- [Contributing](#contributing)

---

## Fairness & Bias  
*(newest first)*

- **Does Compression Exacerbate Large Language Models’ Social Bias?**  
  Ganaie et al., 2025  
  https://openreview.net/pdf?id=iFFfAbFp8a

- **How Quantization Shapes Bias in Large Language Models**  
  Marcuzzi et al., 2025  
  https://arxiv.org/abs/2508.18088

- **Understanding the Unfairness in Network Quantization**  
  Zhang et al., ICML 2025  
  https://icml.cc/virtual/2025/poster/43689

- **Fair-GPTQ: Bias-Aware Quantization for Large Language Models**  
  Proskurina et al., 2025  
  https://arxiv.org/abs/2509.15206

- **Downsized and Compromised? Assessing the Faithfulness of Model Compression**  
  Kamal & Talbert, 2025  
  https://arxiv.org/abs/2510.06125

- **How Does Quantization Affect Multilingual LLMs?**  
  Li et al., EMNLP Findings 2024  
  https://aclanthology.org/2024.findings-emnlp.935/

- **You Never Know: Quantization Induces Inconsistent Biases in Vision-Language Foundation Models**  
  Slyman et al., 2024  
  https://arxiv.org/abs/2410.20265

- **The Impact of Model Compression on Fairness**  
  Kamal, FLAIRS 2024  
  https://journals.flvc.org/FLAIRS/article/download/135617/140005/260572

- **A Comparative Study on the Impact of Model Compression Techniques on Fairness in Language Models**  
  Ramesh et al., ACL 2023  
  https://aclanthology.org/2023.acl-long.878/

- **Can Model Compression Improve NLP Fairness**  
  Xu & Hu, 2022  
  https://arxiv.org/abs/2201.08542

- **The Effect of Model Compression on Fairness in Facial Expression Recognition**  
  Stoychev & Gunes, 2022  
  https://arxiv.org/abs/2201.01709

---

## Robustness & Reliability  
*(newest first)*

- **Decomposed Trust: Exploring Privacy, Adversarial Robustness, Fairness, and Ethics of Low-Rank LLMs**  
  Asante et al., 2025  
  https://arxiv.org/abs/2511.22099

- **Model Hemorrhage and the Robustness Limits of Large Language Models**  
  Ma et al., 2025  
  https://arxiv.org/abs/2503.23924

- **Compressed but Compromised? A Study of Jailbreaking in Compressed LLMs**  
  NeurIPS Lock-LLM Workshop 2025  
  https://openreview.net/pdf?id=OkNfb8SmLh

- **Benchmarking Post-Training Quantization in LLMs: A Comprehensive Taxonomy**  
  Zhou et al., 2025  
  https://arxiv.org/abs/2502.13178

- **Compression Scaling Laws: Unifying Sparsity and Quantization**  
  Zhang et al., 2025  
  https://arxiv.org/html/2502.16440v1

- **BiLLM: Pushing the Limit of Post-Training Quantization for LLMs**  
  Liu et al., 2024  
  https://arxiv.org/abs/2402.04291

- **Exploiting LLM Quantization**  
  Egashira et al., NeurIPS 2024  
  https://proceedings.neurips.cc/paper_files/paper/2024/file/496720b3c860111b95ac8634349dcc88-Paper-Conference.pdf

- **Model Compression in Practice: Lessons Learned from Real Deployments**  
  ACM, 2024  
  https://dl.acm.org/doi/10.1145/3613904.3642109

- **Towards Understanding Model Quantization for Reliable Deep Neural Network Deployment**  
  Hu et al., 2023  
  https://orbilu.uni.lu/bitstream/10993/59236/1/CAIN2023_quantization%20%281%29.pdf

---

## Calibration & Confidence  
*(newest first)*

- **Preserving LLM Capabilities through Calibration Data Curation**  
  He et al., NeurIPS 2025  
  https://arxiv.org/abs/2510.10618

- **Self-Calibration for Language Model Quantization and Pruning**  
  Li et al., 2025  
  https://arxiv.org/abs/2410.17170

- **Beware of Calibration Data for Pruning Large Language Models**  
  Ji et al., ICLR 2025  
  https://openreview.net/forum?id=x83w6yGIWb

- **Interpreting the Effects of Quantization on LLMs**  
  Singh et al., 2025  
  https://arxiv.org/pdf/2508.16785

- **When Quantization Affects Confidence of Large Language Models?**  
  Proskurina et al., NAACL 2024  
  https://aclanthology.org/2024.findings-naacl.124/

- **On the Impact of Calibration Data in Post-Training Quantization and Pruning**  
  Williams & Aletras, ACL 2024  
  https://aclanthology.org/2024.acl-long.544/

- **PD-Quant: Post-Training Quantization Based on Prediction Difference Metric**  
  Liu et al., 2022  
  https://arxiv.org/abs/2212.07048

- **An Underexplored Dilemma between Confidence and Calibration in Quantized Neural Networks**  
  Xia et al., 2021  
  https://arxiv.org/abs/2111.08163

---

## Toxicity & Safety  
*(newest first)*

- **Assessing Safety Risks and Quantization-Aware Safety-Patching Framework (Q-Resafe)**  
  Patel et al., ICML 2025  
  https://icml.cc/virtual/2025/poster/44278

- **Decoding Compressed Trust: Scrutinizing the Trustworthiness of Efficient LLMs Under Compression**  
  Hong et al., ICML 2024  
  https://arxiv.org/abs/2403.15447

- **Beyond Perplexity: Multi-dimensional Safety Evaluation of LLM Compression**  
  Xu et al., EMNLP Findings 2024  
  https://aclanthology.org/2024.findings-emnlp.901/

- **HarmLevelBench: Evaluating Harm-Level Compliance and the Impact of Quantization on Model Alignment**  
  Belkhiter et al., 2024  
  https://arxiv.org/abs/2411.06835

---

## Contributing

Contributions are welcome.

- Papers must study **undesired effects of compression**
- Use arXiv abstract links when available
- List the final venue if accepted
- Keep entries concise and consistent
- Papers may appear in multiple sections

### Formatting example

```md
- **Paper Title**  
  Author et al., Venue Year  
  https://arxiv.org/abs/XXXX.XXXXX
```
