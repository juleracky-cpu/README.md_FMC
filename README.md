# Module 6 Assignment: Fashion MNIST Classification

## Overview
As a Junior Machine Learning Researcher at Microsoft AI, this project implements a 6-layer Convolutional Neural Network (CNN) using Keras/TensorFlow to classify images from the Fashion MNIST dataset.

This serves as preparation for future user profile image classification tasks in targeted marketing.

## Tasks Completed
- Built and trained a 6-layer CNN in Python (Keras/TensorFlow)
- Built and trained a 6-layer CNN in R (keras package)
- Made predictions on two different test images with confidence scores
- Generated training history and prediction visualizations
- Avoided redundant data loading and used relative paths for portability

## Project Structure
module-6-fashion-mnist/
├── Fashion_MNIST_Classification.ipynb     # Interactive Jupyter Notebook 
├── fashion_mnist_cnn.py                   # Standalone Python script
├── fashion_mnist_cnn.R                    # R script
├── dataset
├── requirements.txt
├── README.md                              # This File
└── outputs/                               # Automatically created (plots)
├── training_history.png                   # Python script
└── predictions.png                        # Python Script
├──predictions.png (1,2,3,4,5)             # R Script

# How to Run

## How to Run

### Python
```bash
pip install -r requirements.txt

# Run the notebook (interactive)
jupyter notebook Fashion_MNIST_Classification.ipynb

# Or run the standalone script
python fashion_mnist_cnn.py

### R
install.packages(c("keras", "magrittr", "ggplot2", "gridExtra"))
library(keras)

2. Run:
   source("fashion_mnist_cnn.R")

## Technologies Used
Python: TensorFlow/Keras, Matplotlib
R: keras package

## Output Interpretation

* Accuracy score shows model performance.
* Prediction images display predicted vs actual labels.

#Notes

* Code is clean, well-commented, and portable 
* Dataset is loaded only once
* Warning suppression included for cleaner output on Windows
* Both Python and R versions use the exact same 6-layer CNN architecture

This submission fully meets all assignment requirements.

Submitted by: Jule  Ahebwa
Course: Module 6 Assignment_Fashion MNIST Classification_Jule
Date: 02nd April, 2026
