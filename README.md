# dog_breed_classification
Using image data of different dog breeds, detect breeds using CNN

Project Details
Convolutional Neural Network(CNN) based image classification project for Data Science Nanodegree program of Udacity. The notebook follows a self-made CNN architecture and then improve its accuracy ont est set using transfer learning.

## Project Instructions
Folder Structure:
- saved_models folder that contains weights from trained models
- dog_app.ipynb - Jupyter notebook containing all the code
- images folder that contains sample images

This repository doesn't include any dataset. But can be downloaded through the code inside the notebook.

## Steps Taken: 
- Step 0: Import Datasets
- Step 1: Detect Humans
- Step 2: Detect Dog
- Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
- Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
- Step 5: Write Your Algorithm
- Step 6: Test Your Algorithm

## Architectures used:
- Self made CNN architecture using Keras
- VGG-16 Architecture
- Resnet50

## Libraries Used:
- Keras (Convolutional Neural Network)
- OpenCV (Human Face Detection)
- Matplotlib (Plot Images)
- Numpy (Numerical computations)

## Accelerating the Training Proecess
GPU must be used to train the models quickly. Although pre-trained model weights can be loaded to classify new images on the current classifier.
