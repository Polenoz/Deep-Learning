# Deep Learning Project

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polenoz/Deep-Learning/blob/main/DeepLearning_Projekt.ipynb)

This repository reproduces the Deep Learning exercise from the course `Python für Data Science, Maschinelles Lernen & Visualization` for `Prüfungsaufgabe 1`.

## Overview

This project demonstrates how to build and evaluate a deep learning model using TensorFlow and Keras. The model classifies bank notes as real or fake based on the features in the dataset. The notebook includes data exploration, preprocessing, model training, and evaluation.

## Contents

- `DeepLearning_Projekt.ipynb`: Jupyter notebook with the full workflow
- `Bank_Note_Data.csv`: Dataset used for training and evaluation
- `requirements.txt`: List of required Python packages

## Dataset

The dataset (`Bank_Note_Data.csv`) contains features for bank note authentication and whether a bank note is real or fake. It is loaded directly from the repository when running the notebook.

## How to Run

### Google Colab (Recommended)

1. Click the **Open in Colab** badge above.
2. The notebook will open in Google Colab.
3. Run all cells from top to bottom in order.
4. No manual data upload is required.

### Local (Jupyter)

1. Clone or download this repository.
2. Install the dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook with Jupyter:

```bash
jupyter notebook DeepLearning_Projekt.ipynb
```

4. Run all cells from top to bottom.

## Expected Results

The notebook should reproduce the deep learning example on the bank note dataset and show:

- data exploration and visualizations
- data preprocessing
- deep learning model training
- classification report
- confusion matrix

Example output:

```text
              precision    recall  f1-score   support

           0       1.00      0.99      0.99       222
           1       0.98      0.99      0.99       190

    accuracy                           0.99       412
   macro avg       0.99      0.99      0.99       412
weighted avg       0.99      0.99      0.99       412

[[219   3]
 [  1 189]]
```

## Notes

This repository is intended as one of the required exercise repositories for `Prüfungsaufgabe 1`.
