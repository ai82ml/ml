#  Project Name　:　Anomaly detection

Script to determine good and defective products using Convolutional Autoencoder

## Table of Contents
- [Overview](#overview)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Contact](#contact)

## Overview
The purpose of this project is to implement a machine learning model that determines good and defective products and detects anomalies.
First, train the Convolutional Autoencoder using only image data of normal objects. Then, by looking at the difference between the reconstructed image when the unknown image is used as input data and the input image, areas that could not be successfully reconstructed are visualized as abnormal areas.
Also, the difference between the input image and the output image is defined as the abnormality level, and if this abnormality level exceeds a threshold value, the input image is determined to be abnormal data, and if it does not exceed this abnormality level, the input image is determined to be normal data. The threshold value is determined to maximize the F value.

## Getting Started
I used Python to do this project.
### Prerequisites
the following libraries are required.
numpy==1.24.3
pandas==1.5.3
matplotlib==3.7.1
tensorflow==2.14.0
Pillow==10.0.1
scikit-learn==1.3.1
keras==2.14.0

## Installation
Please install the libraries listed in the prerequisites.
(command example)
pip install numpy
pip install pandas
pip install matplotlib
pip install tensorflow
pip install Pillow
pip install scikit-learn
pip install tensorflow
pip install keras

## Contact
For questions or bug reports, please use the following methods:
 Email: mt4.auo@gmail.com
