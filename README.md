# Custom-Object-Detection

This repository contains scripts and resources for training and using an object detection model with TensorFlow.

## Overview

The goal of this project is to detect and localize objects within images. We use TensorFlow, an open-source machine learning framework developed by Google, for training and inference.

## Contents

- `Images/`: Folder containing images used for training and testing the object detection model.
- `Data_preparation.ipynb`: Jupyter Notebook for preparing the data, including tasks like data cleaning, preprocessing, and generating label maps.
- `generate_tfrecord.py`: Python script for generating TensorFlow record files, which are used for training.
- `labelmap.txt`: Text file containing label mappings, mapping class names to numerical labels.
- `test.csv` and `train.csv`: CSV files containing annotations or metadata for the training and testing datasets.
- `test.record` and `train.record`: TensorFlow record files containing serialized data for training.

## Getting Started

To use this project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/Object-Detection-TensorFlow.git
   
2. Install Dependencies
   ```bash
   pip install -r requirements.txt
  
3. Prepare your data using Data_preparation.ipynb.

4. Generate TensorFlow record files using generate_tfrecord.py.

5. Train your object detection model using TensorFlow.



