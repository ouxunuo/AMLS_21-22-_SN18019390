# AMLS_21-22-_SN18019390

## 1. Introduction of the task

### Brain Tumor Classification (MRI) dataset
an image-based dataset containing MRI scans of human brain. The images are in grayscale and are manually classified into 4 classes based on tumor type.  

Citation: Sartaj Bhuvaji, Ankita Kadam, Prajakta Bhumkar, Sameer Dedge, and Swati Kanchan, “Brain Tumor Classification (MRI).” Kaggle, 2020, doi: 10.34740/KAGGLE/DSV/1183165.
### Task A Binary task
Build a classifier to identify whether there is a tumor in the MRI images.
### Task B Multiclass task
Build a classifier to identify the type of tumor in each MRI image (meningioma tumor, glioma tumor, pituitary tumor or no tumor).

## 2. Organisation and role of the files

### 2.1 image_pre_process
This folder contains two files that could process the raw data and split them into 4 labels

### 2.2 Dataset
The processed image set is given, you could download them to your PC  from these URL directly and enter the local path in each file.
#### Task_A_image: https://drive.google.com/file/d/10olgxB8su8RcFC6SRC4vurVW3-4Lm_21/view?usp=sharing
#### Task_B_train_image: https://drive.google.com/file/d/1OSe05s-p1DHe3r3rMQL0faDOCDbUFVEs/view?usp=sharing
#### Task_B_test_image: https://drive.google.com/file/d/1tLmn9xO1TIjm6JE3MvmBTtfzIACSk96I/view?usp=sharing

### 2.3 Task_A
Including a SVM model file (jupyter notebook) for binary classification

### 2.4 Task_B
Including a CNN model file (jupyter notebook) for multiclass classification
