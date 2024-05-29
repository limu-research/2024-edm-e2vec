# Overview

This repository contains supplementary materials for the following conference paper:

Yuma Miyazaki, Valdemar Švábenský, Yuta Taniguchi, Fumiya Okubo, Tsubasa Minematsu, and Atsushi Shimada.\
**E2Vec: Feature Embedding with Temporal Information for Analyzing Student Actions in E-Book Systems**.\
In Proceedings of the 17th International Conference on Educational Data Mining ([EDM 2024](https://educationaldatamining.org/edm2024/)).

# File description

### `1_Preprocessing.ipynb`
Convert EventStream log into Text file.\
See Section 3.2 in the paper.

### `2_train_fastText.ipynb`
Train fastText with preprocessed text.\
See Section 3.3 in the paper.

### `3_Making_CodeBook.ipynb`
Make CodeBook for Aggregation.
Perform k-means++ clustering for action vectors.\
See Section 3.4.1 in the paper.

### `4_Embedding_and_Aggregation.ipynb`
Generate students vector in one lecture course.

### `5_At-risk_prediction.ipynb`
Predict students grade with student vectors.\
See Section 7 in the paper.

# How to cite

If you use or build upon the materials, please use the BibTeX entry below to cite the original paper (not only this web link).

```bibtex
@inproceedings{Miyazaki2024e2vec,
    author    = {Miyazaki, Yuma and \v{S}v\'{a}bensk\'{y}, Valdemar and Taniguchi, Yuta and Okubo, Fumiya and Minematsu, Tsubasa and Shimada, Atsushi},
    title     = {{E2Vec: Feature Embedding with Temporal Information for Analyzing Student Actions in E-Book Systems}},
    booktitle = {Proceedings of the 17th International Conference on Educational Data Mining},
    series    = {EDM '24},
    location  = {Atlanta, GA, USA},
    publisher = {International Educational Data Mining Society},
    month     = {07},
    year      = {2024},
    numpages  = {9},
}
```
