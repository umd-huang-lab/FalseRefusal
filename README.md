# Automatic Pseudo-Harmful Prompt Generation for Evaluating False Refusals in Large Language Models
by [Bang An*](https://bangann.github.io/), [Sicheng Zhu*](https://schzhu.github.io/)
, [Ruiyi Zhang](https://zhangry868.github.io/)
, [Michael-Andrei Panaitescu-Liess](https://scholar.google.se/citations?user=MOP6lhkAAAAJ&hl=lv)
, [Yuancheng Xu](https://yuancheng-xu.github.io/)
, [Furong Huang](http://furong-huang.com/)

[[Project Page](https://phtest-frf.github.io/)]  [[Paper](https://arxiv.org/abs/2409.00598)]  [[Dataset](https://huggingface.co/datasets/furonghuang-lab/PHTest)]

## About

<img src="php_examples.png" alt="Alt text" width="100%" />

Safety-aligned large language models (LLMs) sometimes falsely refuse pseudo-harmful prompts, like "how to kill a mosquito," which are actually harmless. Frequent false refusals not only frustrate users but also provoke a public backlash against the very values alignment seeks to protect. In this paper, we propose the first method to auto-generate diverse, content-controlled, and model-dependent pseudo-harmful prompts. Using this method, we construct an evaluation dataset called PHTest, which is ten times larger than existing datasets, covers more false refusal patterns, and separately labels controversial prompts. We evaluate 20 LLMs on PHTest, uncovering new insights due to its scale and labeling. Our findings reveal a trade-off between minimizing false refusals and improving safety against jailbreak attacks. Moreover, we show that many jailbreak defenses significantly increase the false refusal rates, thereby undermining usability. Our method and dataset can help developers evaluate and fine-tune safer and more usable LLMs.

## Dataset
Please find the PHTest dataset on [Hugging Face](https://huggingface.co/datasets/furonghuang-lab/PHTest)

## Code
PHTest is generated based on a controllable text-generation technique called [AutoDAN](https://arxiv.org/abs/2310.15140). Our method offers a tool for automatic model-targeted false refusal red-teaming.

Code is coming soon!


## Citing

If you find our work helpful, please cite it with:

```bibtex
@inproceedings{
an2024automatic,
title={Automatic Pseudo-Harmful Prompt Generation for Evaluating False Refusals in Large Language Models},
author={Bang An and Sicheng Zhu and Ruiyi Zhang and Michael-Andrei Panaitescu-Liess and Yuancheng Xu and Furong Huang},
booktitle={First Conference on Language Modeling},
year={2024},
url={https://openreview.net/forum?id=ljFgX6A8NL}
}
