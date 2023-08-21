# Document Image Classification using Deep Convolutional Neural Networks (CNNs)

**Indoml-datathon 2022 Project**

This repository contains the code and findings of a project presented at the Indoml-datathon in 2022. The project focuses on classifying and searching document images using deep convolutional neural networks (CNNs) with transfer learning techniques. The goal is to achieve accurate classification of document images by leveraging the hierarchical abstractions learned by CNNs.

## Table of Contents

- [Introduction](#introduction)
- [Feature Selection and Method Description](#feature-selection-and-method-description)
- [Experimental Results](#experimental-results)
- [Figures and Tables](#figures-and-tables)
- [Novelty](#novelty)
- [Conclusion](#conclusion)
- [Citation and References](#citation-and-references)

## Introduction

This project presents a method for document image classification using deep convolutional neural networks (CNNs) and transfer learning. The core idea is to utilize the hierarchical features learned by deep neural networks to capture concise and descriptive representations of document scenes or objects. A comparison is made with other alternatives, demonstrating the superiority of the proposed approach. The dataset used for this project is derived from the RVL-CDIP dataset, containing a total of 16,000 images divided into multiple classes, each with 1,000 images.

## Feature Selection and Method Description

The primary model employed in this project is a 2D CNN-based model incorporating custom dropout and flattened layers. The architecture is built upon the InceptionResNetV2 framework with pretrained image mesh weights. This combination allows for efficient feature extraction and abstraction, crucial for accurate document image classification.

## Experimental Results

The project underwent training for a total of 90 epochs, yielding an impressive accuracy score of 90.60% and a loss of 0.2907. These results underscore the effectiveness of the selected model architecture and training approach.

## Figures and Tables

The project provides figures and tables illustrating the process of training and testing the InceptionResNetV2 model in three distinct phases. These visual aids facilitate a deeper understanding of the model's performance and progression.

## Novelty

The novelty of this project lies in the utilization of the InceptionResNetV2 model, which combines optimal architectures from ResNet and InceptionNet. By harnessing the strengths of both architectures, the model efficiently captures hierarchical features and promotes faster computation.

## Conclusion

In conclusion, the project demonstrates that an existing model, when equipped with pre-trained weights, outperforms expectations for document image classification. The approach's success underscores the significance of transfer learning and the capability of deep CNNs to extract intricate features from document images.

## Citation and References

- [1] A. W. Harley, A. Ufkes, K. G. Derpanis, "Evaluation of Deep Convolutional Nets for Document Image Classification and Retrieval," in ICDAR, 2015

- [2] Zifeng Wu, Chunhua Shen, Anton van den Hengel, Wider or Deeper: Revisiting the ResNet Model for Visual Recognition, Pattern Recognition, Volume 90, 2019. https://doi.org/10.1016/j.patcog.2019.01.006.

- [3] Analysis of Convolutional Neural Networks for Document Image Classification. [Online] Available at: https://ieeexplore.ieee.org/abstract/document/8270002

- [4] Szegedy, C., Ioffe, S., Vanhoucke, V., & Alemi, A. (2016). Inception-v4, Inception-ResNet and the Impact of Residual Connections on Learning. arXiv. https://doi.org/10.48550/arXiv.1602.07261

- [5] Chris Tensmeyer; Tony Martinez Analysis of Convolutional Neural Networks for Document Image Classification. [Online] Available at: https://ieeexplore.ieee.org/abstract/document/8270002

For more details, refer to the full paper: [Analysis of Convolutional Neural Networks for Document Image Classification](https://ieeexplore.ieee.org/abstract/document/8270002)
