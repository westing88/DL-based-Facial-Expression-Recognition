# Facial Expression Recognition using Deep Learning (FER-2013 Dataset)

This project focuses on facial emotion recognition using various deep learning models trained on the **FER-2013 dataset**. It includes full pipelines for data preprocessing, augmentation, training, and evaluation across multiple architectures.

## 🧠 Models Implemented
- Convolutional Neural Network (CNN)
- ResNet
- MobileNet
- Vision Transformer (ViT)

## 📁 Project Files
- `Data_processing.ipynb`: Data cleaning and formatting
- `Data_Augmentation.ipynb`: Image augmentation (flipping, rotation, cropping)
- `CNN.ipynb`: Implementation and training of a basic CNN model
- `ResNet&MobileNet.ipynb`: ResNet and MobileNet training and evaluation
- `ViT Model.ipynb`: Vision Transformer training and evaluation
- `FER-2013.zip` *(not included here for storage reasons)*: Dataset required for training

## ⚙️ Environment Setup

Before running the code, install the required Python packages:

```bash
pip install torch torchvision numpy matplotlib scikit-learn
