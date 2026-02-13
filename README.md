# Liver Tumor Segmentation using U-Net

## Overview
This project implements a deep learning-based medical image segmentation model for liver tumor detection using U-Net and transfer learning techniques.

## Objective
To perform pixel-wise segmentation of liver tumors from medical imaging data using convolutional neural networks.

## Model Architecture
- Encoder–Decoder (U-Net style)
- ResNet50 backbone (transfer learning)
- Upsampling-based decoder layers
- Binary segmentation output

## Dataset
Medical imaging dataset (MRI/CT-based)
(Note: Dataset is not included in this repository.)

## Training
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Validation split used
- Model trained for 10 epochs

## Evaluation
Performance evaluated using pixel-wise segmentation metrics.

## Technologies Used
- TensorFlow / Keras
- NumPy
- OpenCV
- Nibabel

## Future Improvements
- Implement Dice Loss
- Add data augmentation
- Improve model generalization

---

Author: Aysel Rahimli
