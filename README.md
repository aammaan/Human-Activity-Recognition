
# Human Activity Recognition using Kernelized SVM

You can find the dataset here [link](https://drive.google.com/file/d/1lJk8WC08Q4yaWWG-8eRKZAN6LUdlp7Mm/view?usp=drive_link)


<img src="https://github.com/aammaan/Human-Activity-Recognition/blob/main/image.png" alt="Classes" width="400"/>



## Abstract

The Human Activity Recognition (HAR) model differentiates various human activities with broad applications across different domains. This project involves extensive data preprocessing and exploratory data analysis (EDA) on the HAR dataset, followed by applying Kernelized SVM to classify images into distinct activity classes.

## Introduction

In this study, we utilize image data and associated labels to classify 15 different actions, including sitting, clapping, dancing, using a laptop, and more. The dataset comprises 'training.csv' and 'test.csv' files providing filenames and corresponding labels, along with raw image data in 'training' and 'test' directories.

## Data Pre-processing Techniques

- **Class Imbalance**: The dataset shows a balanced distribution with 840 images per class.
- **Data Distribution**: The training set contains 12,600 images, and the testing set has 5,400 images.
- **Histogram Plots**: RGB histograms reveal dataset characteristics and per-class distributions.
- **Standardization**: Despite non-Gaussian distribution, standardization aids in scaling pixel values.
- **Normalization**: Essential for feature scaling, ensuring consistent input scales.
- **Image Size Consistency**: Maintaining original image sizes for effective kernelized SVM processing.

## Advanced Preprocessing

Advanced techniques include Canny and Bilateral filters for edge detection and noise reduction, enhancing image quality for feature extraction.

## Feature Extraction and Model Training

Features like Histograms of Oriented Gradients (HOG), HSV color histograms, and Local Binary Patterns (LBP) are extracted and combined for SVM classification. Various kernels (linear, RBF, polynomial) are tested for optimal model performance.

## Results

- **HOG + HSV + LBP Features**: Achieved 35% accuracy with a polynomial kernel.
- **Feature Enhancement**: Bilateral filtering and Sobel edge detection improved feature extraction, while SIFT features showed promise for nuanced image analysis.

## Conclusion

This project highlights the efficacy of Kernelized SVMs in HAR, demonstrating the importance of preprocessing and feature extraction techniques for accurate activity classification from image data.

