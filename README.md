# Deep Learning Techniques for Classification of Orthodontic Photos
## Project Overview
This project aims to develop a system that classifies dental images into five distinct treatment categories using advanced machine learning techniques. Our approach utilizes neural networks, focusing on visual image transformations to enhance classification accuracy.

## Objective
The primary goal is to categorize orthodontic images into five treatment classes:

1. SOFT: Requires soft treatments; images typically show regular dentition.
2. SEMI MEDIUM: Needs semi-medium treatments; teeth are not perfectly regular.
3. MEDIUM: Requires medium treatments; teeth are irregular, with potential additional issues like occlusion.
4. SEMI HARD: Needs semi-hard treatments; dentition is irregular, often accompanied by other issues.
5. HARD: Requires hard treatments; dentition is irregular and associated with multiple problems.
## Dataset Preparation
**Data Collection**: Images were sourced from the "Sorridi" website.
**Treatment Analysis**: Treatment recommendations were analyzed from patient data.
**Image Processing**: Includes cropping, padding, resizing, and organizing into specific categories.
**Multiple Datasets**: Two datasets were created, one with only frontal images and another with multiple views.

## Methodology
- CNN from Scratch: Implemented a convolutional neural network with four convolutional blocks, global average pooling, and a classification block.
- CNN with Early Exit: Added early exit blocks to the CNN for faster inference and efficient classification.
- MobileNetV2: Utilized a pre-trained MobileNetV2 model tailored for resource-constrained environments and fine-tuned for dental image classification.
- VGG16 and VGG19: Applied fine-tuning to these models, adapting them specifically for orthodontic photo classification.
- DenseNet121 and InceptionV3: Employed these architectures for their robust feature extraction capabilities.
- NASnet5-Large and Vision Transformers: Explored advanced architectures for enhanced classification performance.
- Swin Transformer v2 and ConvNeXt V2: Investigated these models for their hierarchical structure and efficient feature learning.
## Performance Evaluation
The project includes a detailed analysis of model performance using various metrics such as accuracy and confusion matrices. Each model's effectiveness is evaluated based on its ability to classify images into the correct treatment categories.

## Challenges and Solutions
Image Variation: Addressed the challenge of varying image angles and quality through data augmentation and specialized network architectures.
Class Imbalance: Tackled class imbalance by employing specific training strategies and evaluating models on balanced metrics.

## Future Directions
Enhance model robustness through further experimentation with different architectures and training strategies.
Explore the integration of additional data sources and modalities to improve classification accuracy.
