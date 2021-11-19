## Problem Statement

The purpose of this project is to examine the following three scenarios:
1. If a deep learning model can be created to accurately classify brain tumor MRI images into one of four classes: glioma, meningioma, pituitary tumor, or benign.
2. If a deep learning model can be created to accurately classify if colon tissue histopathological images are cancerous or not.
3. If a deep learning model can be created to accurately classify lung tissue histopathological images into one of three classes: adenocarcinoma, squamous cell carcinoma, or benign.  

### Datasets used in this project
  #### Brain Tumor Classification (MRI) Images
  The Brain Tumor MRI scans are from a dataset on [Kaggle](https://www.kaggle.com/sartajbhuvaji/brain-tumor-classification-mri).   The scans contain images with four different labels – glioma tumor, meningioma tumor, pituitary tumor, and no tumor.  The images can also be downloaded from [google drive](https://drive.google.com/drive/folders/1oLa6T7Bua6nUEbm97Vggz3jQ1hg4ALDx?).
  #### Lung Cancer Histopathological Images
  The Lung Cancer Images are from a dataset on [Kaggle](https://www.kaggle.com/andrewmvd/lung-and-colon-cancer-histopathological-images). The scans contain images with three different labels: lung adenocarcinoma (lung_aca), lung squamous cell carcinomas (lung_scc), and lung benign (lung_benign). The images can also be downloaded from [google drive](https://drive.google.com/drive/folders/14tG6gHRl0exJANZg3xa6JFUT1Xi8RH-a).
  #### Colon Cancer Histopathological Images  
  The Colon Cancer Images are from a dataset on [Kaggle](https://www.kaggle.com/andrewmvd/lung-and-colon-cancer-histopathological-images). The scans contain images with two different labels: colon adenocarcinoma (colon_aca) and colon benign (colon_benign). The images can also be downloaded from [google drive](https://drive.google.com/drive/folders/1fT3wLL8gxKrBca7bJ910LwzS0kZAAFXZ).  
  
---
For each of the three datasets, the following models were created:
1. A Convolutional neural network (CNN) model built from scratch using Keras.  
2. A CNN model built on top of the ResNet50 model architecture using the fastai library.
3. A CNN model built on top of the VGG19 model architecture using the fastai library.
