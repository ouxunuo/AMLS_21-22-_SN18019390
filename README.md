# AMLS_21-22-_SN18019390

## 1. Introduction of the task
This project is aim to build a Machine Learning based classification system. In order to help with classification of MRI images of brain tumor, application of automated classification techniques using Machine Learning(ML) and Artificial Intelligence(AI)has consistently shown higher accuracy than manual classification. Hence, proposing a system performing detection and classification by using Deep Learning Algorithms using ConvolutionNeural Network (CNN) or non-deep learning model would be helpful to doctors all around the world.
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
The processed image set is given, you could download them to your PC from these URL directly and enter the local path in each file.  

**Task_A_image:** https://drive.google.com/file/d/10olgxB8su8RcFC6SRC4vurVW3-4Lm_21/view?usp=sharing  
**Task_B_train_image:** https://drive.google.com/file/d/1OSe05s-p1DHe3r3rMQL0faDOCDbUFVEs/view?usp=sharing  
**Task_B_test_image:** https://drive.google.com/file/d/1tLmn9xO1TIjm6JE3MvmBTtfzIACSk96I/view?usp=sharing  

### 2.3 Task_A
Including a SVM model file (jupyter notebook) for binary classification

### 2.4 Task_B
Including a CNN model file (jupyter notebook) for multiclass classification

## 3. Run the code
All program files are using jupyter notebook with Python 3.8.5

### 3.1 image_pre_process
Runnging `data_process_for_train.ipynb` and `data_process_for_test.ipynb`  
Before running the code, make sure you have downloaded the given training set and testing set. Then start the file with jupyter notebook and follow the instruction in it.  
After finishing the code, the output folder would be in the same position as the folder path of the code.
### 3.2 Task_A
Running `SVM_model.ipynb`  
I strongly recommend you download the dataset by URL in 2.2, and copy the path to the correct position in the code. Then follow the running sequence in jupyter notebook.
### 3.3 Task_B
Running `CNN_model.ipynb`  
I strongly recommend you download the dataset by URL in 2.2, and copy the path to the correct position in the code. Then follow the running sequence in jupyter notebook.  
For the three model, you could only choose one model to run and jump to prediction till end. To run other ones, you need to restart kernel and clear the output and run code from begining to end.

## 4. Necessary packages
Please see `package.txt` above, it contains all the version of packages.
### Core packages
Python == 3.8.5  
TensorFlow-gup == 2.5.0  
Keras == 2.5.0  
matplotlib == 3.5.0  
numpy == 1.19.5  
OpenCV == 4.5.4.60  
pandas == 1.3.4  
...
