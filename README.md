# TensorFlow Classification Project

In this project, a neural network model is built using TensorFlow and Keras. The goal is to classify bank notes as real or fake based on the given features.

## Dataset

The project uses the file:

- Bank_Note_Data.csv

Make sure the file is in the same directory as the notebook.

## Required libraries

This project uses the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow
- keras

## How to run

You can run the notebook in Google Colab:

- Open the notebook
- Upload the dataset file
- Run all cells

You can also run it locally:

- Install the required libraries
- Open the notebook with Jupyter
- Run all cells

Example installation:

pip install pandas numpy matplotlib seaborn scikit-learn tensorflow keras jupyter

## What is done in this notebook

- The dataset is loaded and explored
- Data is prepared for training
- Features are scaled
- A neural network model is created with Keras
- The model is trained
- Predictions are made
- The results are evaluated
- A random forest model is also used for comparison

## Evaluation

The model is evaluated using:

- Confusion matrix
- Classification report

These metrics show how well the model performs on the test data.
