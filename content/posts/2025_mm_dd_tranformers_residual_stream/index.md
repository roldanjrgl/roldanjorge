---
author: "Jorge Roldan"
date: "2026-01-02"
title: "Implementing and Training a Transformer (Residual Stream perspective)"
categories: ["article"]
ShowToc: true
ShowBreadCrumbs: false
draft: true
---
<!-- post_id:100 -->

# Outline
- Introduction
- Explain the GPT-2 architecture
- What's this residual stream in a transformer 
- Why is it important
- How to access the residual stream before and after every layer
- this is a test for reference [^deep_residual] and [^a_math_framework_for_transformers]


# Nomencleature

| Name                                   | Symbol      | Variable  | Dimension                      | Description     |
| -------------------------------------- | ----------- | --------- | ------------------------------ | --------------- |
| Model Size                             | $d_{model}$ | `d_model` | $scalar$                       |                 |
| Input                                  | $X$         | `x`       | $[d_{vocab} \times d_{model}]$ |                 |
| batch                                  | $b$         | `b`       | $scalar$                       | Bath dimension  |
| Num heads                              | $n$         |           | $scalar$                       | Number of heads |
| Sequence length                        | $s$         |           | $scalar$                       |                 |


# Architecture of the Transformer
{{< figure id="transformer_architecture.png" src="./transformer_architecture.png" alt="kevin32b_benchmarks" caption="Kevin-32B correctess and performance results " width="700"  >}}


# References
[^deep_residual]: K. He, X. Zhang, S. Ren, and J. Sun, “Deep Residual Learning for Image Recognition,” Dec. 10, 2015, arXiv: arXiv:1512.03385. doi: 10.48550/arXiv.1512.03385.
[^a_math_framework_for_transformers]: “A Mathematical Framework for Transformer Circuits.” Accessed: Sep. 21, 2025. [Online]. Available: https://transformer-circuits.pub/2021/framework/index.html
