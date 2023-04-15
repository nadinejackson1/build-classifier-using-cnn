# Cats vs Dogs Kaggle Challenge

This repository contains the code for the Cats vs Dogs Kaggle Challenge for the programming assignment in Course 1- Week 4 of Deeplearning.ai's "Convolutional Neural Networks" course.

### Project Description

In this project, we use the full Cats vs Dogs dataset of 25k images to build a classifier using convolutional neural networks. The objective is to build a classifier that can distinguish between cats and dogs in images with high accuracy.

### Installation

Clone this repository:

    git clone https://github.com/nadinejackson1/build-classifier-using-cnn.git

### Usage

The main file for this project is cats_vs_dogs.ipynb, which can be run in Jupyter Notebook or Google Colab. The following functions should be implemented and tested:

    create_train_val_dirs: This function creates directories for the training and validation sets.

    split_data: This function splits the data into training and validation sets.

    train_val_generators: This function creates the data generators for the training and validation sets.

    create_model: This function creates the convolutional neural network.

The notebook also includes code for training the model, making predictions, and evaluating the model's performance.

### Dataset

The Cats vs Dogs dataset can be downloaded from the following Kaggle competition page: https://www.kaggle.com/c/dogs-vs-cats/data.

After downloading the dataset, create a directory called data and extract the dataset files to it.

### Evaluation

The accuracy of the model will be evaluated using the training history file. The file should be saved as history.pkl in the root directory of the project.

### Credits

This project is based on the Cats vs Dogs Kaggle Challenge and was developed as a programming assignment for Deeplearning.ai's "Convolutional Neural Networks" course.
