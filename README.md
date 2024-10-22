# Pea Plant Quality Assessment Using Custom CNN

## Project Overview

This project implements a Convolutional Neural Network (CNN) model to assess the quality of pea plants using deep learning techniques. The primary goal is to classify images of pea plants into various quality categories based on their visual appearance, enabling early detection of diseases and growth issues. This can significantly enhance agricultural practices by providing farmers and researchers with tools to monitor crop health efficiently.

## Table of Contents

- [Motivation](#motivation)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training Process](#training-process)
- [Results](#results)
- [Usage](#usage)
- [Future Work](#future-work)
- [Acknowledgments](#acknowledgments)

## Motivation

With the increasing demand for food production and the challenges posed by pests and diseases, it is crucial to develop efficient monitoring systems for crops. This project aims to contribute to precision agriculture by utilizing computer vision and machine learning techniques to assess the quality of pea plants. By automating the assessment process, we can provide timely information to farmers, enabling them to make informed decisions regarding crop management.

## Dataset

The dataset used in this project consists of labeled images of pea plants, collected from various sources. The images represent different conditions and quality levels, including healthy plants, diseased plants, and those affected by environmental factors. The dataset is divided into training, validation, and testing sets to ensure the model's generalization capabilities.

## Model Architecture

The CNN model is designed with several layers, including:

- **Convolutional Layers**: For feature extraction from the input images.
- **Pooling Layers**: To reduce the dimensionality of the feature maps and retain essential information.
- **Fully Connected Layers**: For classification based on the extracted features.

The architecture is customized to optimize performance for the specific task of pea plant quality assessment.

## Training Process

The model is trained using the training dataset, employing techniques such as data augmentation to enhance its robustness. The training process involves:

- **Loss Function**: Categorical cross-entropy.
- **Optimizer**: Adam optimizer for efficient convergence.
- **Metrics**: Accuracy to monitor the model's performance during training and validation.

The model's performance is evaluated using the validation dataset, and hyperparameters are fine-tuned accordingly.

## Results

Upon completion of the training process, the model is evaluated on the test dataset. The results demonstrate the model's accuracy and effectiveness in classifying pea plant quality. Detailed performance metrics, including confusion matrices and classification reports, are provided to illustrate the model's strengths and weaknesses.

## Usage

To use the model for assessing pea plant quality, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/abdullahzunorain/Pea_Plant_Quality_Assessment_using_custom_CNN.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Pea_Plant_Quality_Assessment_using_custom_CNN
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Load the model and input an image of a pea plant for quality assessment.

## Future Work

Future enhancements for this project may include:

- Expanding the dataset with more diverse samples to improve model robustness.
- Experimenting with different deep learning architectures (e.g., transfer learning with pre-trained models).
- Developing a web or mobile application to make the model accessible to users in the agricultural sector.

## Acknowledgments

Special thanks to the contributors and researchers in the field of plant health monitoring for their insights and resources that made this project possible.

---
