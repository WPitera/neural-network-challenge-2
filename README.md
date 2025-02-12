# Attrition Prediction Model

## Overview

This Jupyter Notebook (`attrition.ipynb`) contains an end-to-end machine learning pipeline for predicting employee attrition. The notebook is structured into two main parts:

1. **Preprocessing** – Data cleaning, encoding categorical variables, and scaling numerical features.
2. **Model Creation, Compilation, and Training** – Implementing a neural network model using TensorFlow/Keras to predict employee attrition.

## Dataset

The dataset is loaded from an external CSV file:

```
https://static.bc-edx.com/ai/ail-v-1-0/m19/lms/datasets/attrition.csv
```

It contains various employee attributes relevant for attrition analysis.

## Dependencies

To run this notebook, ensure you have the following Python libraries installed:

```
pip install pandas numpy scikit-learn tensorflow
```

### Key Libraries Used:

- `pandas` – For data manipulation
- `numpy` – For numerical operations
- `scikit-learn` – For data preprocessing and model evaluation
- `tensorflow.keras` – For building and training the neural network model

## Usage

1. Open the notebook in Jupyter or Google Colab.
2. Run the preprocessing cells to clean and prepare the dataset.
3. Execute the model training cells to build and train the neural network.
4. Evaluate the model’s performance using accuracy metrics.

## Output

- A trained neural network model that predicts employee attrition.
- Model evaluation metrics, including accuracy and loss.

