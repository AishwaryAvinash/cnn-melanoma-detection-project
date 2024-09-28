# Melanoma Disease Detection Using CNN 

In this project, a multiclass classification model is built using a custom convolutional neural network (CNN) in TensorFlow to detect melanoma and other skin diseases from images. The model helps dermatologists by automating the diagnosis process, potentially reducing manual effort.

**Note:** Original files related to this project are not shared publicly as they are part of my academic assignments.

## Table of Contents:
- [Project Structure](#project-structure)
- [General Info](#general-info)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## Project Structure

This repository consists of the following key files:

1. **Aishwarya_Avinash_Melanoma_Detection_project.ipynb**: A well-documented Python code file (Jupyter Notebook) that includes all the steps for data preprocessing, model building, training, and evaluation using a custom CNN.

2. **Melanoma Detection Assignment Explanation and Conclusion.pdf**: A detailed report explaining the project's key components:
   - **Problem Statement**: The significance of early melanoma detection.
   - **The Dataset**: Description and source of the ISIC dataset used.
   - **Approach**: Steps taken to preprocess data, handle class imbalance, and build the CNN model.
   - **Model Development**: How the CNN was developed, overfitting handled, and augmentation techniques applied.
   - **Conclusion**: Summary of findings and model performance.

## General Info:
Melanoma is a type of cancer that can be deadly if not detected early, accounting for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort required in diagnosis.

We are provided with a dataset consisting of 2,357 images of malignant and benign oncological diseases, formed from the International Skin Imaging Collaboration (ISIC). The dataset contains the following diseases:
1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion

**Link to the dataset**: [Google Drive - Dataset](https://drive.google.com/drive/folders/13d9icXqHbgyGDKn2wtYg-XiBhdfnzf2B?usp=drive_link)

## Technologies Used (Libraries and Computation):
- **Google Colab** (utilizing the power of T4 GPU for execution)
- **TensorFlow** (version: 2.13.0)
- **Matplotlib** (version: 3.7.1)
- **Pathlib** (version: 1.0.1)


## Conclusions:
- The base model performed well on the training set but poorly on the validation set, indicating signs of overfitting.
- To mitigate overfitting, data augmentation techniques like rotation, flipping, and zoom were applied, alongside dropout layers, which helped address overfitting but reduced the accuracy on both training and validation sets.
- Class imbalance was detected, and further augmentation techniques were used to improve model performance. This resulted in the best-performing model so far.

## Acknowledgements:
While this project was a group assignment, I took a leading role in handling much of the work, including data preprocessing and model development. The project was guided by Mr. **Sayan Dey**, Upgrad Instructor, whose notebook provided valuable steps to achieve optimal results.
