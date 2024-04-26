# Mask-Off-GAN-Face-Mask-Removal-using-Generative-Adversarial-Networks
MaskOff GAN is a project aimed at removing masks from human faces using Generative Adversarial Networks (GANs). The project uses TensorFlow and implements a conditional GAN architecture to generate realistic facial images without masks based on input images with masks.
# Project Overview
The project consists of the following components:
# Data Preprocessing
Loading and processing of training and test images.
Random jittering and normalization of images for data augmentation.
# Model Architecture
Generator: A U-Net style generator network that takes masked face images as input and outputs predicted face images without masks.
Discriminator: A PatchGAN discriminator that discriminates between real and generated images.
# Loss Functions
Generator Loss: Combines adversarial loss (GAN loss) with L1 loss to encourage realistic and high-quality image generation.
Discriminator Loss: Computes the adversarial loss for the discriminator.
# Training and Evaluation
Training loop that optimizes both generator and discriminator networks using TensorFlow's built-in training utilities.
Evaluation of the trained model by generating sample images and visualizing model performance.v
# Requirements
The project requires the following dependencies:

TensorFlow 2.x
Python 3.x
OpenCV
Matplotlib
NumPyUsage
# Data Preparation:
Place your training and test images in the specified directory structure (train/*.jpg for training images and test/*.jpg for test images).
# Dataset 
Link:https://drive.google.com/drive/folders/1Ol4YbZXDdZ_Dlc_lkRJ9Kvx3xiF2lgRZ?usp=drive_link
# Model Training:
Execute the training script (train.py) to start training the MaskOff GAN model.
# Model Evaluation:
Use the trained model to generate face images without masks from input images with masks.

# Directory Structure

![image](https://github.com/Zidane-263/Mask-Off-GAN-Face-Mask-Removal-using-Generative-Adversarial-Networks/assets/145212977/9355d544-c40a-4225-916b-29a7f4aa337f)

# Acknowledgements
This project was inspired by the Pix2Pix GAN architecture and adapted to the specific task of face mask removal.



