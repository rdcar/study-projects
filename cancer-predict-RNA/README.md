# RNA Sequencing Cancer Prediction

## Project Description

This repository is dedicated to a study project focused on predicting cancer based on RNA sequencing data. The data were collected from [The Cancer Genome Atlas (TCGA)](https://www.cancer.gov/ccg/research/genome-sequencing/tcga), an international program that characterizes over 33 types of cancer. Each row represents a sample from an individual, with columns representing different microRNAs and their expression levels. Expression values range from $[0, \infty]$, where values close to zero indicate low expression and higher values indicate high expression. Labels include TP (primary solid tumor) indicating cancer and NT (normal tissue).

## Objective

The goal of this project is to build a model to predict cancer presence based on RNA sequencing data.

## Data Sources

1. [The Cancer Genome Atlas Program](https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga)
2. [Micro RNA](https://en.wikipedia.org/wiki/MicroRNA_sequencing)
3. [Sklearn Pipeline](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html)

## Results

The model with the best result was the Logistic Regression model with the dimensionality reduction through the PCA (Principal Component Analysis) technique, achieving an accuracy of 98%, precision of 99.5%, recall of 99.6% and F1-Score of 99.5%.

## Future Work

As my studies progress, I will continue to improve the model's hyperparameters and experiment with different algorithms to enhance prediction accuracy.