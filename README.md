# Multi-Accuracy in Quantum Machine Learning
**Emma Yang and Ricardo Skewes, CS 226R: Topics in Theory for Society: The Theory of Algorithmic Fairness (Spring 2024)**

This repository contains a series of notebooks for training quantum classifiers, comparing them to classical machine learning algorithms, and evaluating their quantum multi-accuracy as defined in our project.

Prerequisites for running these notebooks include `scikit-learn` and `qiskit`, which can both be installed in `pip` or `conda`.

- `qsvc_multiaccuracy.ipynb` trains a Quantum Support Vector Classifier on a dataset of credit loan defaults in Taiwan in 2005, and evaluates its hybrid quantum multi-accuracy with respect to demographic factors. **The simulations from this notebook are detailed in our project report.**
- `vqc_fair_datasets.ipynb` trains a Variational Quantum Classifier on the same dataset
- `vqc_german_credit.ipynb` trains a VQC on a dataset of 1,000 loan applicants and their creditability classification collected in Germany. This dataset was used in a prior work on quantum fairness, _Verifying Fairness in Quantum Machine Learning_.
