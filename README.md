# Face Mask Detection

Face masks have become an essential part of our daily lives due to the global pandemic. Detecting whether individuals are wearing masks can be crucial in various public settings. This project aims to detect the presence of face masks on individuals using both classical machine learning and deep learning methods.

## Table of Contents
- [1 Exploratory Data Analysis](#1-exploratory-data-analysis)
  - [1.1 Get to know Directory Structure](#11-get-to-know-directory-structure)
  - [1.2 Get to know File Format](#12-get-to-know-file-format)
- [2 Get to know each image shape and mode](#2-get-to-know-each-image-shape-and-mode)
  - [2.1 Central Tendency](#21-central-tendency)
- [3 Classical Machine Learning using Sklearn Library](#3-classical-machine-learning-using-sklearn-library)
  - [3.1 Model Selection: Holdout Strategy](#31-model-selection-holdout-strategy)
  - [3.2 Feature Extraction: RGB2GRAY -> HogTransformer -> Standarized](#32-feature-extraction-rgb2gray--hogtransformer--standarized)
  - [3.3 Pipelining](#33-pipelining)
  - [3.4 HyperParameter Tuning: GridSearch](#34-hyperparameter-tuning-gridsearch)
  - [3.5 Score and Evaluation](#35-score-and-evaluation)
- [4 Deep Learning using Tensorflow Library](#4-deep-learning-using-tensorflow-library)
  - [4.1 Data augmentation](#41-data-augmentation)
  - [4.2 Modeling](#42-modeling)
  - [4.3 Score and Evaluation](#43-score-and-evaluation)
- [5 Classical Machine Learning VS Deep Learning Score and Evaluation](#5-classical-machine-learning-vs-deep-learning-score-and-evaluation)

## 1 Exploratory Data Analysis

### 1.1 Get to know Directory Structure
- Explanation of how the dataset is organized and where the data files are located.

### 1.2 Get to know File Format
- Insight into the type of image files, their format, and any associated metadata.

## 2 Get to know each image shape and mode
- Understanding the dimensions, resolution, and type of each image in the dataset.

### 2.1 Central Tendency
- Statistical analysis to understand the mean, median, mode, and other tendencies of the data.

## 3 Classical Machine Learning using Sklearn Library

### 3.1 Model Selection: Holdout Strategy
- Details on how the data was split between training, validation, and test sets.

### 3.2 Feature Extraction: RGB2GRAY -> HogTransformer -> Standarized
- Explanation of how features are extracted from images using the RGB2GRAY method, HogTransformer, and standardization.

### 3.3 Pipelining
- Description of the pipeline used for preprocessing and model building.

### 3.4 HyperParameter Tuning: GridSearch
- Details on the grid search strategy to optimize hyperparameters for the model.

### 3.5 Score and Evaluation
- Overview of model performance, accuracy, precision, recall, and other evaluation metrics.

## 4 Deep Learning using Tensorflow Library

### 4.1 Data augmentation
- Techniques used to augment the dataset to improve the model's performance.

### 4.2 Modeling
- Architecture and design of the neural network used for face mask detection.

### 4.3 Score and Evaluation
- Performance metrics for the deep learning model, including accuracy, loss, precision, and recall.

## 5 Classical Machine Learning VS Deep Learning Score and Evaluation
- Comparative analysis of both methodologies and a summary of which method performed better and why.

---

**Contributors:** Riyan Sthefanus Nainggolan

For further details or questions, please contact ryansthefanus@gmail.com.
