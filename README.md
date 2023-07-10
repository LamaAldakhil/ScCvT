# ScCvT

This repository contains code to train and test the ScCvT model for the purpose of classifying skin cancer. The repository is intended to support the academic paper "Classification of Skin Cancer Using a Convolutional Vision Transformer Model."

# Dataset

The dataset used is the HAM10000 dataset which is available to use here: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T. This dataset consists of 10,015 dermoscopic images of skin lesions labeled with one of seven categories: actinic keratosis, basal cell carcinoma, benign keratosis-like lesions, dermatofibroma, melanoma, melanocytic nevi, and vascular lesions.

# Installation 

*This code requires you to have a Hugging Face account*

The following packages need to be installed for the code to work:

### **For training:**

Transformers

Datasets

Accelerate

Evaluate

Torch

Torchvision

### **For testing:**

Transformers

Torch

huggingface_hub

Pandas

Numpy

Scikit-learn

Pillow

# Usage

*Important note: loading the dataset will differ depending on how it is stored.*
