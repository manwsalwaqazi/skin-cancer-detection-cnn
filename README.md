# Skin Cancer Detection Using CNN

## Project Description
This project uses a **Convolutional Neural Network (CNN)** to classify skin lesions as **benign** or **malignant**.  
The model is based on **MobileNetV2** and uses multiple image preprocessing techniques, including:

- **Color normalization**
- **Segmentation / cropping**
- **Data augmentation** (flipping, rotation)
- **Resizing and normalization**

Class imbalance is handled using **class weights** during training. The project evaluates model performance using **accuracy, confusion matrix, and ROC curve**.

---

## Dataset
The dataset used is **HAM10000 (Human Against Machine 10000)**.  

To run this project:

1. Download the dataset: [HAM10000 on Kaggle](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)  
2. Create a folder `data/` in the project root.  
3. Place `HAM10000_metadata.csv` inside `data/`.  
4. Place all images inside `data/images/`.

---

## Installation
1. Clone this repository:

```bash
git clone https://github.com/manwsalwaqazi/skin-cancer-detection-cnn.git
cd skin-cancer-detection-cnn
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage
1. Open skincancer_detection_final.ipynb in Jupyter Notebook.
2. Run the notebook cells sequentially:
    * Data loading & preprocessing → saves processed images in processed_images/
    * Model training → trains CNN using MobileNetV2
    * Evaluation → shows accuracy, confusion matrix, ROC curve
3. Preprocessed images and results will be automatically saved.

## Results
**Training Accuracy & Loss**

<img width="1005" height="461" alt="image" src="https://github.com/user-attachments/assets/57e4407c-9425-4850-94c6-8e1a8a0153bc" />

**Confusion Matrix**

<img width="544" height="447" alt="image" src="https://github.com/user-attachments/assets/f0388862-18b6-40a6-80ee-3ef73f1d9f0e" />

**ROC Curve**

<img width="687" height="535" alt="image" src="https://github.com/user-attachments/assets/bfa463a3-4cc1-4fef-8a59-74f43e76e7fb" />

## Key Highlights

- Built a CNN model (MobileNetV2) for skin lesion classification.
- Applied advanced preprocessing and augmentation for better accuracy.
- Handled class imbalance with class weights.
- Achieved 76% test accuracy.
- Visualized performance with confusion matrix and ROC curve.

## References

HAM10000 Dataset

## License

This project is for educational purposes.
