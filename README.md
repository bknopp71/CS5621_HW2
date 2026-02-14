Silver Image Dataset Project
Overview

This project contains a dataset of JPEG images used to detect the presence of silver in mineral specimens using machine learning and computer vision techniques. The repository includes image data, associated metadata, and code used for preprocessing and model development.

Project Structure
project/
│── data/
│   ├── silver/            # Images containing silver-bearing minerals
│   └── non_silver/        # Images without silver content
│
│── metadata/              # CSV / JSON files describing images and labels
│
│── code/                  # Python scripts and notebooks for preprocessing and modeling
│
│── README.md              # Project documentation
Data Description

Image Format: JPEG (.jpg / .jpeg)

Classes: Binary classification (silver vs. non_silver)

Labeling Method: Images are labeled based on their folder location.

Purpose: Used for supervised machine learning and image classification tasks.

Metadata

The metadata/ folder contains structured information associated with each image, such as:

File name

Class label

Source information (when available)

Additional descriptive attributes

Metadata is stored in:

.csv format for tabular analysis

.json format for flexible data exchange

Code

The code/ folder includes scripts and notebooks used for:

Loading and organizing images

Data preprocessing (resizing, normalization)

Training/testing dataset splits

Model development and evaluation

Intended Use

This dataset supports:

Binary image classification (silver detection)

Training Convolutional Neural Networks (CNNs)

Educational research in data science and AI

Testing computer vision workflows

Requirements

Typical tools used with this dataset include:

Python 3.x

TensorFlow / Keras or PyTorch

Scikit-learn

OpenCV

Jupyter Notebook or Google Colab

Notes

Image resolution and lighting conditions may vary.

Preprocessing is recommended before model training.

Dataset is intended for academic and research use.

Author

Brent Knopp
University of Idaho – Data Science Program
