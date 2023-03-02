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

## References
* [AREnets project](https://github.com/nicolay-r/AREnets)
