The purpose of this project is to examine the following three scenarios:
1. If a deep learning model can be created to accurately classify brain tumor MRI images into one of four classes: glioma, meningioma, pituitary tumor, or benign.
2. if a deep learning model can be created to accurately classify if colon tissue histopathological images are cancerous or not.
3. If a deep learning model can be created to accurately classify lung tissue histopathological images into one of three classes: adenocarcinoma, squamous cell carcinoma, or benign.  

If successful, the models could be used as both a pre-screener and post-screener for the images. Pre-screening could be performed immediately after the image was developed (before being viewed by a doctor or medical professional) and could flag images that need immediate review. Post-screening images (after images are classified by a doctor or medical professional) could ensure that the classification is consistent.

This project will create and evaluate the following three deep learning models to examine if they can be used to classify brain tumor MRI images with high accuracy: 
1. A Convolutional neural network (CNN) model built from scratch using Keras.  
2. A CNN model built on top of the ResNet50 model architecture using the fastai library.
3. A CNN model built on top of the VGG19 model architecture using the fastai library.
