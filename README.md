# NAT_vs_AT

This repository contains the code and data for ACL2024 paper: What Have We Achieved on Non-autoregressive Translation? You may find the paper here: https://arxiv.org/abs/2405.12788

## Overview
In this paper, we systematically evaluate four representative NAT methods across various dimensions. The evaluated models include:

[Vanilla NAT](https://openreview.net/forum?id=B1l8BtlCb)

[CMLM](https://openreview.net/forum?id=I2Hw58KHp8O)

[Mgmo](https://aclanthology.org/2022.emnlp-main.339)

[CTC](https://aclanthology.org/D18-1336)

[DAT](https://proceedings.mlr.press/v162/huang22m.html). 


## Evaluation Dimensions
The evaluation covers several key dimensions to provide a comprehensive understanding of NAT methods:

WMT: Standard translation benchmark.

Compositional Generalization: Ability to generalize to novel compositions of seen elements.

Cross-Domain: Performance on data from different domains.

Input Perturbations: Robustness to changes in input data.

## Acknowledgment
We thank colleagues from [Lan-bridge](http://www.lan-bridge.com/) for examining data and evaluating results. 

## Citation
If you find this repository useful in your research, please consider citing our paper:

```bibtex
@misc{li2024achieved,
      title={What Have We Achieved on Non-autoregressive Translation?}, 
      author={Yafu Li and Huajian Zhang and Jianhao Yan and Yongjing Yin and Yue Zhang},
      year={2024},
      eprint={2405.12788},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
