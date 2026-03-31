# Face Mask Detection using CNN

## Description
This project uses a Convolutional Neural Network (CNN) to detect whether a person is wearing a face mask or not.  
The system can be used for real-time monitoring, public safety, and awareness during pandemics.

## Dataset
- Two classes: `with_mask` and `without_mask`  
- Dataset can be downloaded from Kaggle: [Face Mask Dataset](https://www.kaggle.com/datasets/ashishjangra27/face-mask-dataset)  
- Total images: ~3,800 (3,067 training + 766 validation)

## Features
- Trains a CNN from scratch on face mask dataset
- Provides demo on uploaded images
- Model achieves **>93% validation accuracy**
- Easy to run in Colab

## How to Run
1. Open the notebook: `train_and_demo.ipynb`
2. Follow cells to:
   - Train the model (optional if already trained)
   - Run demo by uploading images
3. Install required libraries:

```bash
pip install -r requirements.txt
