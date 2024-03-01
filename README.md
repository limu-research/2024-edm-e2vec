# Overview

This repository contains supplementary materials for the following conference paper:

Anonymous Authors.\
E2Vec: Feature Embedding with Temporal Information for Analyzing Student Actions in E-Book Systems.\
Submitted for review in the 17th International Conference on Educational Data Mining ([EDM 2024](https://educationaldatamining.org/edm2024/)).

# File description
## `1_Preprocessing.ipynb`
Convert EventStream log into Text file.
See Section 3.2 in paper.

## `2_train_fastText.ipynb`
Train fastText with preprocessed text.
See Section 3.3 in paper.

## `3_Making_CodeBook.ipynb`
Make CodeBook for Aggregation.
Perform k-means++ clustering for action vectors.
See Section 3.4.1 in paper.

## `4_Embedding_and_Aggregation.ipynb`
Generate students vector in one lecture course.

## `5_At-risk_prediction.ipynb`
Predict students grade with student vectors.
See Section 7 in paper.
