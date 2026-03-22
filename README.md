
# Deep Learning Project

**Note:** This project was developed and tested primarily in **Google Colab**. All instructions and code are fully compatible with Colab, and the recommended way to run and reproduce results is via the Colab badge below.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Polenoz/Deep-Learning/blob/main/DeepLearning_Projekt.ipynb)

## Overview
This project demonstrates how to build a neural network model using TensorFlow and Keras to classify bank notes as real or fake. The notebook includes data loading, preprocessing, model creation, training, and evaluation.

## Contents
- `DeepLearning_Projekt.ipynb`: Jupyter/Colab notebook with the full workflow
- `Bank_Note_Data.csv`: Dataset used for classification
- `requirements.txt`: List of required Python packages

## Dataset
The dataset (`Bank_Note_Data.csv`) is loaded automatically from the repository when running in Colab.

## How to Run

### Google Colab (Recommended)
1. Click the **Open in Colab** badge above.
2. The notebook will open in Google Colab.
3. Run all cells from top to bottom. The dataset loads automatically from the repository.
4. No manual data upload or extra setup is required.

### Local (Jupyter, also possible)
1. Clone or download this repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook with Jupyter: `jupyter notebook DeepLearning_Projekt.ipynb`
4. Run all cells.

## Expected Results
- Data exploration and visualizations of bank note features
- Training and evaluation of a neural network model
- Example output:

```
              precision    recall  f1-score   support

           0       1.00      0.99      0.99       222
           1       0.98      0.99      0.99       190

    accuracy                           0.99       412
   macro avg       0.99      0.99      0.99       412
weighted avg       0.99      0.99      0.99       412

[[219   3]
 [  1 189]]

```


## Evaluation

- Confusion matrix
- Classification report
