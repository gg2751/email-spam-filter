# Spam Filter Project

[Last Updated in 2023. Commited on June 12, 2024 for Archiving Purposes.]

In this project, we built a spam filter using various machine learning techniques. The notebook covers dataset preparation, feature selection, and implementing different classifiers:

1. Naive Bayes
    - Bernoulli NB with Binary Features
    - Multinomial NB with Binary Features
    - Multinomial NB with Term Frequency (TF) Features
2. Support Vector Machines (SVM)

## Dataset

The dataset used in this project contains labeled emails categorized as spam or ham (non-spam). The dataset is preprocessed to remove unnecessary characters and tokens.

## Feature Selection Using Information Gain

Information gain is used to select the most relevant features for the classification task. It demonstrates the calculation and selection of features based on their information gain values.

## Directory Structure

For running this project, ensure the following directory structure:
```
lingspam_public/
└── lemm_stop/
    ├── part1/
    │   ├── file1.txt
    │   ├── file2.txt
    │   └── ...
    ├── part2/
    │   ├── file1.txt
    │   ├── file2.txt
    │   └── ...
    ├── part3/
    │   ├── file1.txt
    │   ├── file2.txt
    │   └── ...
    ├── ...
    ├── part9/
    │   ├── file1.txt
    │   ├── file2.txt
    │   └── ...
    └── part10/
        ├── file1.txt
        ├── file2.txt
        └── ...
```
