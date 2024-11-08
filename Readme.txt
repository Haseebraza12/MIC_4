Medical Image Computing Assignment 4


This project implements two main tasks:
1. Medical Image Classification using PathMNIST Dataset
2. Image Segmentation using Pascal VOC 2012 Dataset

Requirements
-----------
- Python 3.12
- PyTorch
- torchvision
- medmnist
- matplotlib
- scikit-learn
- seaborn

Task 1: PathMNIST Classification
------------------------------
The first task implements a CNN model for classifying medical pathology images using the PathMNIST dataset. The model architecture includes:
- 2 convolutional layers
- Max pooling layers
- 2 fully connected layers
- Output layer for 9-class classification

Key features:
- Data visualization capabilities
- Model training with validation
- Performance evaluation using confusion matrix
- Model checkpointing after each epoch
- Final model saved as 'bscs22115_final_model.pth'

Task 2: Image Segmentation
------------------------
The second task implements a U-Net architecture for semantic segmentation using the Pascal VOC 2012 dataset. Features include:
- Encoder-decoder architecture with skip connections
- Image resizing to 128x128
- Binary segmentation output
- Performance evaluation using confusion matrix
- Final model saved as 'unet_model.pth'

Usage
-----
1. Install required packages:
   pip install torch torchvision medmnist matplotlib scikit-learn seaborn

2. Run the notebooks in order:
   - First execute Task 1 cells for classification
   - Then execute Task 2 cells for segmentation

3. Models will be automatically saved after training



Author: Haseeb Ur Rehman (BSCS22115)