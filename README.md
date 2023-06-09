# The application of Hybrid deep learning Approach to evaluate chest ray images for the diagnosis of pneumonia in children

This repository presents a comprehensive collection of Python notebooks featuring state-of-the-art deep learning models for the accurate diagnosis of pneumonia from chest X-ray (CXR) images. Pneumonia remains a major cause of morbidity and mortality worldwide, particularly among children in developing nations. Early and precise diagnosis of pneumonia plays a crucial role in reducing its associated health risks.

## Abstract

The aim of this research is to evaluate the diagnostic accuracy of a novel hybrid machine learning vision-based model for pneumonia diagnosis using CXR images. The proposed model combines the power of convolutional neural networks (CNNs) and tree-based algorithms, specifically random forest and light gradient boosting machine (LGBM). By leveraging a dataset of 5,856 digital CXR images, consisting of both normal and pneumonia cases, the hybrid model achieves exceptional diagnostic accuracy of over 95%. The results surpass those of previous studies, including the application of deep learning algorithms such as Chex-Net with 121 layers.

## Models

Pretrained Models (Based on ImageNet Dataset)
1. **ResNet Architecture:** Explore various ResNet models, including ResNet 18, 34, 50, 101, and 152, pretrained on the extensive ImageNet dataset.
2. **VGGNet Architecture:** Discover the potential of VGGNet models, particularly VGG16 and VGG19, which have been trained on ImageNet and excel in learning intricate features.
3. **GoogleNet Architecture:** Experience the ingenuity of GoogleNet and Inception models, renowned for their exceptional performance in image recognition tasks.
4. **DenseNet Architecture:** Dive into DenseNet models, with a specific focus on DenseNet 121, known for its densely connected layers and robust feature extraction capabilities.
5. **ShuffleNet Architecture:** Witness the efficiency of ShuffleNet, a compact and high-speed model designed for low-memory operations.
6. **MobileNet Architecture:** Explore MobileNet, a lightweight architecture optimized for mobile and embedded devices, delivering excellent performance.
7. **SqueezeNet Architecture:** Discover the brilliance of SqueezeNet, a compact model achieving high accuracy with significantly fewer parameters.

## Hybrid Models Outperforming Pretrained Models
1. **ResNet as Feature Extractor with Random Forest Classifier:** Unleash the power of a pretrained ResNet model as a feature extractor, combined with a Random Forest classifier, to achieve superior performance.

2. **ResNet as Feature Extractor with LightGBM Classifier:** Experience enhanced results by leveraging a pretrained ResNet model as a feature extractor and coupling it with a LightGBM classifier.

Feel free to utilize these meticulously crafted models to facilitate the diagnosis of pneumonia from chest X-ray images. These models have been trained and fine-tuned using advanced techniques, offering an invaluable resource in the fight against this widespread ailment.


## Usage
To get started, follow the instructions in each notebook to load the necessary dependencies and data. Each notebook provides a step-by-step guide, enabling you to understand and implement the models effectively. You can evaluate the performance of different models and experiment with different hyperparameters to optimize the results for your specific use case.

## Contributions
Contributions to this repository are welcome. If you have any improvements, suggestions, or new models to add, please submit a pull request. Let's collaborate and enhance the accuracy and efficiency of pneumonia diagnosis using deep learning techniques.

## Citation
If you find this repository or the hybrid machine learning vision-based model useful in your research or project, please consider citing our paper:
