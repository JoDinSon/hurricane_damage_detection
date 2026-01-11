# Data Sciene Project: Hurricane Damage Detection

This is deep learning image recognition project I did during my Data Science education.

## Objective
The goal was to use transfer learning to build a computer vision tool that could identigy damage from post-hurricane satellite imagery.

## Methodology & Model Selection

I compared several architectures using Transfer Learning on ImageNet weights. I prioritized two metrics:

**Recall (Damage Class):** Because failing to find a damaged building is a higher risk than a false alarm.

**F1-Score:** To ensure the model maintains a healthy balance between precision and recall.

## Results

![ResNet50 Confusion Matrix](diagrams/cm_resnet50.png)