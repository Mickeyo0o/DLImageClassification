# Image Classification with Deep Learning

This project demonstrates a deep learning approach to image classification, created for a Deep Learning course. It also explores additional tests and considerations for developing such models.

## Data

The data comes from Caltech that can be found [here](https://data.caltech.edu/records/mzrjq-6wc02), containing 101 object classes with varying image counts per class. Data is additionally stored in the data folder in the repository.

## Features

* <b>Data Download & Preprocessing:</b> This code includes functions to download, preprocess, and manage class imbalance by capping images per class. We split the data into training and testing sets while maintaining class proportions in both.
* <b>Standardization:</b> Images are standardized using training set statistics to prevent information leakage from the test set.
* <b>Model Development & Evaluation:</b> We provide a deep learning model for image classification, train it, and evaluate its performance. This includes visualization of challenging examples and evaluation metrics. Additionally, functions are included to load and save the model with its weights.
* <b>Experiments:</b> The code explores how the number of classes, number of examples per class, and preprocessing methods can influence the results.

## Usage

To use this notebook, please ensure that all the libraries mentioned in the beginning of the jupyter notebook are installed. (Keep in mind that the project was made on Python 3.9.18 and model training was GPU-accelerated with tensorflow-gpu version). 
Additionally, if you do not wish to install the necessary libraries you can just look at the prerun jupyter notebook, as it contains the output of all the cells.

## Creators

* Kajetan Sulwiński (ekohachi22)
* Mikołaj Marmurowicz (Mickeyo0o)

