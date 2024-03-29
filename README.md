# Multimodal Data Fusion: Classification of Exercise from Accelerometer and Depth Sensor Data
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/github/username/repository/blob/main/notebook.ipynb](https://colab.research.google.com/github/mitunkantipaul/Multimodal-Data-Fusion-Final-Project-2023/blob/main/Final_of_project_work_MEx_classification.ipynb))

## Description

The goal of this project is to develop user-independent pre-processing and classification models to recognize 7 different physical exercises measured by accelerometer (attached to subject's thigh) and depth camera (above the subject facing downwards recording an aerial view). All the exercises were performed subject lying down on the mat. Original dataset have also another acceleration sensor and pressure-sensitive mat, but those two modalities are ommited in this project. There are totally 30 subjects in the original dataset, and in this work subset of 10 person is utilized. A detailed description of the dataset and original data can be accessed in [MEx dataset @ UCI machine learning repository](https://archive.ics.uci.edu/ml/datasets/MEx#). We are providing the subset of dataset in Moodle.

The project work is divided on following phases:

1. Data preparation, exploration, and visualization
2. Feature extraction and unimodal fusion for classification
3. Feature extraction and feature-level fusion for multimodal classification
4. Decision-level fusion for multimodal classification


The results are validated using confusion matrices and F1 scores. F1 macro score is given as
<br>
<br>
$$F1_{\text{macro}} = \frac{1}{N} \sum_{i=1}^{N} F1_i$$
<br>
<br>
where $F1_i = 2  \frac{precision_i * recall_i}{precision_i + recall_i}$, and $N$ is the number of classes.
<br>


#### This was a Final project for the Multimodal Data Fusion course at the University of Oulu for Dec. 2023
