# LegalEval-2023 Task-6C `nclu_team` submissions code

## Installation

![](https://img.shields.io/badge/Python-3.6.9-brightgreen.svg)

```bash
pip install -r dependencies.txt
```

Fist step is to adopt inut processing, provided in:
* `input_orig_convert.py` -- original texts
* `input_v1_convert.py` -- text processor which discards duplicated sentences mentioned simultaneously in both classes (by [thanet-m](https://github.com/thanet-m))
* `input_v2_convert.py` -- text processor which reduce non semantic oriented sentences (v2).

We provide `cnn` and `att-cnn` models from AREnets.

Language models implementation provided in a form of the jupyter notebooks.

## Projects

* [AREnets project](https://github.com/nicolay-r/AREnets)

## Reference
```
@article{rusnachenko2023ncluteam,
  title={nclu\_team at SemEval-2023 Task 6C1 and 6C2: Attention-based Approaches for Large Court Judgement Prediction with Explanation},
  author={Nicolay, Rusnachenko and Thanet, Markchom and Huizhi, Liang},
  booktitle = "Proceedings of the 17th International Workshop on Semantic Evaluation (SemEval-2023)",
  month = jul,
  year = "2023",
  address = "Toronto, Canada",
  publisher = "Association for Computational Linguistics"
}
```
