# Skin Cancer Detection Using CNN

## Description
This project uses a Convolutional Neural Network (MobileNetV2) to classify
skin cancer images as benign or malignant. Multiple preprocessing techniques
(color normalization, segmentation, augmentation) are applied to improve accuracy.

## Dataset
The dataset is not included due to size limits. Download HAM10000 here:
https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000

After downloading:
1. Create a folder `data/` in the project root.
2. Place `HAM10000_metadata.csv` inside `data/`.
3. Place all images inside `data/images/`.

## Installation
Install required packages:

```bash
pip install -r requirements.txt

