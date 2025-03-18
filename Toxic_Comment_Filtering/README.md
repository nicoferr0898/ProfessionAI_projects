# Toxic Comment Filter

## Project Overview

This project aims to build a deep learning model that can filter user comments based on their level of toxicity. The model classifies comments into multiple categories of harmful language.

## Features

- Preprocesses text data to remove non-significant tokens
- Transforms text corpus into sequences
- Utilizes a deep learning model with recurrent layers for multilabel classification
- Predicts toxicity levels across six categories: toxic, severe_toxic, obscene, threat, insult, and identity_hate


## Dataset

The project uses a dataset containing user comments labeled with toxicity categories. The dataset is loaded from an S3 bucket.

## Model Output

At prediction time, the model returns a vector of 6 elements, each containing either 0 or 1, corresponding to the six toxicity categories. For example:

- A non-harmful comment:
- A toxic comment:[^1][^1]


## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TensorFlow/Keras (implied for deep learning)

