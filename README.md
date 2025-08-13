
# Cat vs Dog Image Classifier

This project uses deep learning to classify images as either **Cat** or **Dog**.  
Two models were tested: a **Custom CNN** and **MobileNetV2** (Transfer Learning).

## Features
- Preprocessing of images (resize, normalization, augmentation)
- Training and evaluation of two different models
- Accuracy/Loss graphs for performance comparison
- Sample predictions on test images

## Dataset
- Source: [Kaggle – Cats & Dogs](https://www.kaggle.com/datasets/tongpython/cat-and-dog)
- Images resized to 224×224 pixels  
- Normalized pixel values (0–1 range)  
- Augmentation applied to improve model generalization

## Results
- **Custom CNN**: 87% Accuracy  
- **MobileNetV2**: 92% Accuracy  

MobileNetV2 performed better due to pre-trained weights from ImageNet.

## Repository Contents
- `code/` → Notebooks & scripts for preprocessing, training, and evaluation  
- `models/` → Saved trained models (.h5)  
- `predictions/` → Test images with predicted labels  
- `visuals/` → Accuracy/Loss plots, confusion matrices, and ROC curves  

## How to Run
1. Clone this repository  
2. Install required packages:
   ```bash
   pip install -r requirements.txt
