# IMAGE-CLASSIFICATION-MODEL

*COMPANY *: CODTECH IT SOLUTIONS

*NAME *: MRUNAL TAYDE

*INTERN ID *: CTIS7006

*DOMAIN *: MACHINE LEARNING

*DURATION *: 4 WEEEKS

*MENTOR *: NEELA SANTOSH

SENTIMENT ANALYSIS WITH NLP

1. Project Overview

This project focuses on building a Convolutional Neural Network (CNN) for image classification using the Intel Image Classification Dataset. The primary objective is to develop a deep learning model capable of accurately identifying natural scenes from images across multiple classes. The model is trained using TensorFlow and Keras, and it includes all essential steps such as data preprocessing, model construction, training, evaluation, and prediction. The aim of this project is to create a robust image classifier that demonstrates good accuracy and can be used for academic learning, machine learning tasks, and real-world applications.

The Intel Image Classification problem involves classifying images into six categories: buildings, forest, glacier, mountain, sea, and street. These categories are diverse, and the dataset allows the model to learn different textures, colors, and shapes, making this an ideal project for understanding how CNNs work.

This repository contains the Python code used to process the dataset, build the CNN, train it on the dataset, evaluate performance, and save the final trained model. Due to GitHub’s size restrictions, the full dataset and model file cannot be uploaded directly; instead, download links are provided.

2. Dataset Information

The project uses the Intel Image Classification Dataset, a popular dataset for image classification tasks. The dataset contains approximately 25,000 images spanning six categories. It is widely used in deep learning tutorials and competitions due to its diversity and high-quality images.

Dataset used: Intel Image Classification Dataset
Kaggle Link:
https://www.kaggle.com/datasets/puneet6060/intel-image-classification

The dataset is divided into training, testing, and prediction folders. Each class contains a variety of images collected from natural scenes. For convenience and to keep the GitHub repository lightweight, the full dataset is not uploaded directly to this repository. Instead, users can download it from Kaggle using the link above. A small subset of images may be included in the repository for demonstration purposes.

3. Model Architecture and Training Process

The model used in this project is a CNN built using TensorFlow and Keras. The architecture includes convolutional layers, max-pooling layers, dropout layers to prevent overfitting, dense layers for classification, and softmax output activation. The model is trained using the categorical cross-entropy loss function and optimized using the Adam optimizer. Training involves several epochs where the model learns features from images and improves its classification accuracy. After training, performance is evaluated on the test dataset.

The final model is saved in H5 or SavedModel format. Since GitHub has a 25 MB limit on files, the model is uploaded through Git LFS or provided as a downloadable link through Google Drive.

4. Tools and Technologies Used

Python
TensorFlow
Keras
NumPy
Matplotlib
Google Drive (for dataset and model hosting)
Git and Git LFS (for version control and large file handling)

5. Editor and Development Platform

The project was developed using Jupyter Notebook and Visual Studio Code (VS Code). Both platforms support Python development and provide the flexibility needed for machine learning experimentation. Jupyter Notebook was primarily used for training, visualization, and testing the CNN model, while VS Code was used for organizing the project structure and writing Python scripts.

6. Applications of This Project

This project can be applied in numerous domains where automated image classification is required. Some key applications include:

Scene recognition in photography and media applications
Environmental monitoring and land classification
Smart surveillance systems
Image-based search systems
Educational deep learning demonstrations
Research involving computer vision and CNNs

The project demonstrates the complete workflow of solving a real dataset problem using deep learning and can be extended further for deployment, optimization, or enhancing accuracy using transfer learning.

7. Output

1.Model training

<img width="1000" height="320" alt="Image" src="https://github.com/user-attachments/assets/cb5fb915-26ab-462e-b263-3f9bf278cd60" />

2.Model accuracy graph

<img width="300" height="300" alt="Image" src="https://github.com/user-attachments/assets/739a425d-6c65-4f95-8e5f-db93c3ffae0a" />

3.Model loss graph

<img width="300" height="300" alt="Image" src="https://github.com/user-attachments/assets/55fccda3-1d6c-4d48-894e-adbd83197034" />

4.Accuracy on test dataset

<img width="500" height="150" alt="Image" src="https://github.com/user-attachments/assets/4d8c129a-795f-463f-a60e-a672300ecf93" />

5.Prediction on 3 images 

<img width="300" height="350" alt="Image" src="https://github.com/user-attachments/assets/f461a416-6fac-4e94-bee7-3041e85ac281" />



