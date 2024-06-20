# Dog Skin Diseases Detection Machine Learning Training 

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Datasets](#datasets)
- [Installation](#installation)
- [Training and Evaluation](#training-and-evaluation)


## Introduction

In this project, the machine learning team will create a machine learning model capable of classifying dog skin diseases. We are designing this model using the transfer learning technique. The purpose of this model is to assist pet owners in recognizing the type of skin disease suffered by their pets.

## Features

- Data loading and preprocessing
- Model building and training in Jupyter Notebooks
- Model evaluation and metrics calculation
- Saving and loading trained models
- Visualization of training progress and results

## Technologies Used

- **Programming Language**: Python
- **Libraries**: TensorFlow/PyTorch, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, Jupyter
- **Environment Management**: Anaconda/Virtualenv
- **Configuration**: YAML

## Datasets

he dataset has 7 classes consisting of 6 types of dog skin diseases and 1 healthy skin, with a total of 5280 images. This dataset comes from the internet and we have performed augmentation to increase the amount of data used for training and validation. We selected the most common types of skin diseases experienced by dogs.

(Dataset : https://drive.google.com/drive/folders/1i70NAla5vC25VGDsGGpSu57369pR5kKO?usp=sharing)

## Installation

### Prerequisites

- Python version: 3.10.13
- TensorFlow version: 2.13.0
- NumPy version: 1.26.4
- Matplotlib version: 3.7.5
- TensorFlow.js version: 4.20.0


## Training and Evaluation

The training and evaluation notebooks will save model checkpoints and final models in the `models` directory. Logs and results will be stored for further analysis.
