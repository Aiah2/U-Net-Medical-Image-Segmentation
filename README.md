README FILE

Medical Image Segmentation using U-Net with PCA and t-SNE

PROJECT TITLE
Medical Image Segmentation using U-Net with PCA and t-SNE Visualization

STUDENT INFORMATION

Name: Eric Aiah Amara
Student ID: 9276
Program: BSc Computer Science
Department: Computer Science

Group Members:
Osman Kanu (9192)
Alice Tity Kamara (8944)
Abdulai Idrissa Kamara (8531)
Suluku Joel Conteg (9845)
Hamid Shaw (8794)

Submission Date: 15 March 2026

PROJECT DESCRIPTION

This project presents a machine learning approach for medical image analysis using deep learning techniques. The system applies the U-Net convolutional neural network architecture to perform image segmentation on medical images.

Medical image segmentation involves identifying and separating important regions in medical images such as X-ray, MRI, and CT scans. The U-Net architecture is widely used in biomedical image segmentation because it can classify each pixel in an image and accurately identify regions of interest.

The system processes medical images through several stages including preprocessing, training a segmentation model, generating predicted masks, and visualizing high-dimensional data using dimensionality reduction techniques.

PROJECT OBJECTIVES

The objectives of this project include:

• To implement an image segmentation model using the U-Net architecture
• To preprocess medical image datasets for model training
• To train and evaluate the segmentation model
• To generate segmentation masks for medical images
• To apply dimensionality reduction techniques such as PCA and t-SNE
• To visualize clusters within the medical image dataset

TECHNOLOGIES USED

Programming Language: Python

Libraries and Frameworks:

TensorFlow / Keras
NumPy
Matplotlib
Scikit-learn
OpenCV
Jupyter Notebook / Google Colab

PROJECT FEATURES

The system includes the following functionalities:

• Medical image preprocessing
• U-Net model implementation
• Model training and evaluation
• Image segmentation prediction
• PCA dimensionality reduction
• t-SNE visualization for cluster analysis

DATASET INFORMATION

Image Types Used:

Chest X-ray
Brain MRI
CT Scan Images

Dataset Size: 20 images

Preprocessing Steps:

Image resizing to 128 × 128 pixels

Pixel value normalization

Mask generation for segmentation

Data augmentation including flipping and rotation

PROJECT STRUCTURE

U_Net_Medical_Image_Segmentation

dataset
unet_model.py
train_model.py
predict_evaluate.py
tsne_pca_visualization.py
preprocessing.py
data_loader.py
README.txt

GITHUB REPOSITORY

The full source code for this project is available at the following GitHub repository:

https://github.com/Aiah2/U-Net-Medical-Image-Segmentation

CONCLUSION

This project demonstrates how deep learning techniques such as U-Net can be used for medical image segmentation. By combining convolutional neural networks with dimensionality reduction techniques such as PCA and t-SNE, the system provides a framework for analyzing and visualizing complex medical image datasets.
