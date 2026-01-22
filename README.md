**Lung Cancer Detection using CNN and Transfer Learning (Xception)**

**Project Overview:**
This project implements a deep learning-based lung cancer classification system using CT scan images. A Convolutional Neural Network (CNN) with transfer learning using the pre-trained Xception model is used to classify images into four categories: Normal, Adenocarcinoma, Large Cell Carcinoma, and Squamous Cell Carcinoma.

**Folder Structure:**
LungCancerDetection/
│
├── dataset/
│   ├── train/
│   ├── test/
│   └── valid/
│
├── trained_lung_cancer_model.h5
└── Lung Cancer Detection.ipynb

**How to Run the Project in Google Colab:**
1.Upload the entire LungCancerDetection folder to your Google Drive.
2.Open the notebook Lung Cancer Detection.ipynb in Google Colab.
3.Run the cell to mount Google Drive:
4.from google.colab import drive
5.drive.mount('/content/drive')

**Ensure dataset paths match:**
/content/drive/MyDrive/LungCancerDetection/dataset/

**Run all cells to train or test the model.**

**Model Details:**
1.Pre-trained Model: Xception (ImageNet weights)
2.Optimizer: Adam
3.Loss Function: Categorical Crossentropy
4.Batch Size: 8
5.Epochs: 50
6.Accuracy: ~88% training, ~68% testing

**Output:**
The model predicts the lung cancer category for a given CT scan image.
