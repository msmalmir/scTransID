# scTransID

**scTransID** is a Python package designed for single-cell RNA sequencing data classification using a custom Transformer model. The package provides functions for data preprocessing, model training, and evaluation to streamline the process of analyzing cell type classification.


## Features

- **Data Preprocessing**: Functions for loading, preprocessing, and splitting single-cell data.
- **Transformer Model**: A custom Transformer model for efficient cell-type classification.
- **Training and Evaluation**: Utilities to train the model and evaluate its accuracy and F1 score on new data.
- **Flexible Pipeline**: Modularized code for easy customization and extension.

## Installation

To install the latest version directly from GitHub, use the following command:

```
pip install git+https://github.com/your-username/scTransID.git
```

## Modules

- **data_utils**: Functions for loading, preprocessing, and splitting single-cell data.
- **model**: Defines the Transformer model and its custom layers, including multi-head attention and layer normalization.
- **train**: Contains the training function for model optimization and validation.
- **evaluation**: Functions for evaluating the model on query datasets.

## Requirements

- Python 3.7+
- PyTorch
- scikit-learn
- scanpy

Install these dependencies via `pip`:

```bash
pip install torch scikit-learn scanpy
