
# Alzheimers Disease Detection Using CNN's
 
This project is about Alzheimer's Disease Detection Using CNNs and classifying which type of Alzheimer's.This project aims to improve accuracy, loss, precision, recall, and f1-score.

Our project has been officially recognized and published at an IEEE conference! You can read the complete paper  [here](https://ieeexplore.ieee.org/document/10543787)




## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)



## Introduction
Alzheimer's disease is a progressive neurodegenerative disorder characterized by cognitive decline, memory loss, and impairment in daily functioning. It is the most common form of dementia, affecting millions of individuals worldwide. Early detection and accurate diagnosis of Alzheimer's disease are crucial for timely intervention and effective management of the condition.
Over the years, significant advancements have been made in the field of Alzheimer's disease detection. Researchers have explored various methods and techniques to improve diagnostic accuracy and identify early signs of the disease. These methods encompass a range of approaches, including neuroimaging, biomarker analysis, cognitive assessments, and machine learning algorithms.



## Dataset
The link to access the dataset is provided below. [here](https://www.kaggle.com/datasets/sachinkumar413/alzheimer-mri-dataset)

The dataset used in this project is sourced from Kaggle and comprises 6400 brain scan images categorized into four classes:
- Non Demented
- Very Mild Demented
- Mild Demented
- Moderate Demented
## Installation
To get started with Project, follow these steps:

You can work on this project using code editors or the command line interface (cmd).

When using code editors like VSCode, make sure to open a folder and then open the terminal to run the commands below.

### For VSCode

1.  Clone the repository:
    ```bash
    git clone https://github.com/abdultalha0862/Alzheimer-s-Disease-Detection-using-Deep-Learning.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Alzheimer-s-Disease-Detection-using-Deep-Learning
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
### For CMD
1.  Clone the repository:
    ```bash
    git clone https://github.com/abdultalha0862/Alzheimer-s-Disease-Detection-using-Deep-Learning.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Alzheimer-s-Disease-Detection-using-Deep-Learning
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
**Note :** 
- If your System has no gpu requirements then go for google colab and execute the file
- If you System has gpu support install all the required libraries accoding to gpu ,Cuda packages and Cuddnn packages also  


## Model Architecture

This project utilizes a CNN architecture with the following layers:

- Convolutional layers with ReLU activation
- MaxPooling layers
- Dropout layers for regularization
- Fully connected layers

The architecture is crafted to efficiently capture and understand the unique features within the input images, resulting in precise and reliable classification.



## Training

The training process consits of the following steps:
 - Data preprocessing: Normalizing and augmenting the images.
 - Handling imbalanced datasets using techniques using Smote.
- Splitting the dataset into training, validation, and test sets.
-  Training the CNN model with the processed data.


## Evaluation
The model is checked using various measures like accuracy, Loss,precision, recall, and F1-score.


## Results
This project achieves competitive results in classifying the stages of Alzheimer's disease. Below are the performance metrics:

- **Accuracy**: 99.07%
- **Loss**: 0.036
- **AC**: 99.92%
- **F1-Score**: 99.07%
- **Precision**: 99.07%
- **Recall**: 99.97%

You can find detailed performance metrics and visualizations in the "results" directory.