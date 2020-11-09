# Traffic Signs Recognition (Classification)
This project uses a machine learning model to determine the traffic sign based on the image provided.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Dataset](#dataset)
* [Features](#features)
* [Models](#models)
* [Predictions](#predictions)
* [Dependencies](#dependencies)

## General info 
This project uses LeNet Architecture for constructing neural network to train and evaluate traffic signs. 

## Technologies
* Python
* Anaconda-Navigator 

## Setup
* Download Python: https://www.python.org/downloads/
* Download Anaconda-Navigator: https://www.anaconda.com/products/individual

## Dataset
The original data came from the [German Traffic Sign Recognition Benchmark (GTSRB)](https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign?select=Test.csv). In this case, the image set (train, validation and test) has been transformed into pickle files

### Features
Each image can be classified into one of 43 classes

| Types of Traffic Signs | 
| :---  | 
| `Speed limit (20km/h)` | 
| `End of speed limit (80km/h)` | 
| `No passing for vehicles over 3.5 metric tons` |
| `Dangerous curve to the right` | 
| `Pedestrians` | 
| `Keep left` |
| `End of no passing by vehicles over 3.5 metric tons` |

![Image-1](https://github.com/ibrahim1023/traffic-sign-classification/blob/main/preview_images/image-1.jpg?raw=true "Data Preview")

![Image-2](https://github.com/ibrahim1023/traffic-sign-classification/blob/main/preview_images/image-2.jpg?raw=true "Data Preview")

![Image-3](https://github.com/ibrahim1023/traffic-sign-classification/blob/main/preview_images/image-3.jpg?raw=true "Data Preview")

## Models

| Model | Accuracy (Highest achieved) |
| :---  |     :---:      |
| `Neural Network (LeNet Architecture)` | 97.4 %|

## Predictions 

![Prediction Image](https://github.com/ibrahim1023/traffic-sign-classification/blob/main/preview_images/final.jpg?raw=true "Prediction")

## Dependencies
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Sklearn
