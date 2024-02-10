# Digit Classification with SGDClassifier

## Overview

This project demonstrates the process of building a digit classification model using the `SGDClassifier` from `scikit-learn` library. The dataset used is the MNIST dataset, a collection of 8x8 pixel images of handwritten digits. The goal is to classify these images into one of the ten digit categories (0 through 9).

## Project Structure

- `main.ipynb`: Jupyter notebook containing the full pipeline of loading the dataset, preprocessing the data, training the model, and evaluating its performance.
- `trained_model.pkl`: A pickle file containing the trained model, saved after the training process.

## Objectives

- To preprocess the MNIST dataset for optimal performance of the SGDClassifier.
- To implement a batch data processing mechanism for handling the dataset.
- To train the SGDClassifier with a custom training loop.
- To evaluate the model's performance using metrics such as accuracy, precision, recall, and F1 score.
- To save the trained model for future use.

## Setup and Installation

To run this project, ensure you have the following prerequisites installed:

- Python 3.x
- Jupyter Notebook or JupyterLab
- scikit-learn
- matplotlib
- numpy
- pickle

You can install the necessary libraries using pip:

```bash
pip install notebook scikit-learn matplotlib numpy

```

## Results

After running all the cells in the `main.ipynb` notebook, you will observe detailed evaluation metrics for the trained model. The evaluation includes accuracy, precision, recall, and F1 score on the test dataset. These metrics provide insights into how well the model is performing and where there might be room for improvement.

## Saving the Model

The trained model is saved to a file named `trained_model.pkl`. This file allows the model to be loaded in the future for inference without the need for retraining. Saving the model is crucial for deploying it in real-world applications where predictions are required on new data.

## Conclusion

This project demonstrates a straightforward approach to digit classification using scikit-learn's SGDClassifier. It highlights the significance of data preprocessing and the efficiency of linear models in handling digit classification tasks. The process outlined in this project can be adapted to similar machine learning tasks, showcasing the versatility and power of scikit-learn for building predictive models.

Should you encounter any issues or have further questions, do not hesitate to open an issue in this repository or reach out for support. Contributions to improve the project are always welcome.
