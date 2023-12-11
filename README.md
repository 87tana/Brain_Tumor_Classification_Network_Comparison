# Comparative Analysis of CNN Architectures for Brain Tumor Classification in MRI Images


## Brain_Tumor_Classification

<div align="center">
    <img width="400" src="/images/0_C2YcJf9bavCCu5D0.jpg" alt="Material Bread logo"> 
    <p style="text-align: center;">Photo from Unsplash</p>
</div>



## My Medium Articles on Brain Tumor Classification
- Overview of VGG16, ResNet50, Xception and MobileNet Neural Networks [Medium](https://medium.com/@t.mostafid/overview-of-vgg16-xception-mobilenet-and-resnet50-neural-networks-c678e0c0ee85)
  
- Brain Tumor Classification: A Comparative Analysis of Convolutional Neural Network Architecture on MRI Images [Medium](https://medium.com/p/a7445638a233/edit)

## Introduction:

This project employs **deep learning** to classify brain tumors in MRI scans, emphasizing a comparative analysis of  various **transfer learning** approaches.
Four distinct deep neural network models, namely **VGG16**, **MobileNet, Xception, and ResNet50 models**, we categorize brain tumors into four classes: No Tumor, Glioma, Meningioma, and Pituitary.
These models predict the presence of a brain tumor based on MRI scans, and their comparative analysis offers insights into their performance for brain tumor classification.

- Source of data [Brain Tumor](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri)

## What is brain tumor?

A brain tumor refers to an accumulation of abnormal cells in the brain, presenting a significant health concern due to its aggressive nature. Magnetic Resonance Imaging (MRI) stands out as the most effective technique for detecting brain tumors.

## Data Augmentation and Rescaling

Data augmentation involves applying various transformations to the existing dataset to create additional training examples. These transformations, such as rotation, flipping, or zooming, help enhance the model's ability to generalize and perform well on unseen data. Data augmentation is particularly useful improving the neural network's ability to handle translation invariance.

Apply rescaling to all three datasets (train, validation, and test) for comparability. However, limit data augmentation techniques to the training dataset only, excluding the test and validation sets. This ensures that the model is evaluated on its ability to make predictions on unseen, unaltered data during the testing and validation phases.

## Cohesive Framework:
I tackle this problem through a structured process consisting of six key stages:

1. Description of the Dataset
2. Importing and Preprocessing of Data
3. Augmentation of Data
4. Building the Model
5. Analyzing and Comparing Models
6. Drawing Conclusions

## What is transfer learning?

Transfer learning accelerate deep CNN model training by reusing weights from pre-trained models on a large dataset, such as MobileNet with ImageNet weights. This approach is valuable for smaller datasets, providing an effective shortcut to model training. It involves adapting a pre-trained model to related tasks with limited labeled data, enhancing learning efficiency across various applications like image classification, object detection, etc.


## Compare 4 deep neural network models:

1. **VGG16:**
   - VGG16, a convolutional neural network with 16 weight layers, is a reliable choice as a base model for image classification due to its simplicity and effectiveness. It is characterized by a series of convolutional layers followed by max-pooling layers, ultimately leading to fully connected layers for classification tasks.

1. **MobileNet:**
   - MobileNet is a lightweight neural network architecture designed for mobile and embedded vision applications. It is trained on the ImageNet dataset, and its efficient design makes it suitable for real-time image classification on resource-constrained devices.

2. **Xception:**
   - Xception is an extension of the Inception architecture, and it has also been trained on the ImageNet dataset. Xception focuses on improving the efficiency of learning hierarchical features from data. It has shown strong performance in image classification tasks.

3. **ResNet50:**
   - ResNet50 is part of the ResNet (Residual Network) architecture, specifically ResNet-50, which contains 50 layers. It is a deep convolutional neural network that excels in feature extraction and image classification. ResNet50 has been trained on the ImageNet dataset and has achieved state-of-the-art performance.
  







