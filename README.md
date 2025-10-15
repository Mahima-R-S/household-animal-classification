# household-animal-classification
Cat vs Dog Image Classification using CNN and Transfer Learning


This project implements VGG6 (custom CNN) and VGG16 (transfer learning) models to classify cat and dog images.

Further, fine-tuning of VGG16 improves accuracy significantly.

All experiments were conducted using Google Colab.


Project Overview

-> Model	Description	Accuracy

VGG6-Custom CNN built from scratch	(~80%)

VGG16 (Base) -	Pretrained on ImageNet, frozen conv layers	(~92%)

VGG16 (Fine-Tuned) - Unfrozen top conv layers + trained	(~97%)


-> Key Steps:

1)Dataset Preprocessing (train/test split)

2)VGG6 CNN Model Training

3)Transfer Learning with VGG16

4)Fine-Tuning of Top Layers

5)Visualization of:

  Training/Validation Accuracy & Loss

  Intermediate Layer Activations

  Grad-CAM Heatmaps

