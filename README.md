# Convolutional Neural Network (CNN) Building to Predict Lumbar Spine Disease
> This project was for predicting the location and severity of lumbar spine disease based on MRI images. The Kaggle competition was hosted by the Radiological Society of North America (RSNA).

*Access the Kaggle notebook [here](https://www.kaggle.com/code/gitbyt3/lumbar-spine-eda-cnn-building/notebook).*


## Dataset
The dataset was provided by RSNA and consisted of 147k MRI images as DICOM files. Each image was linked to a particular patient identified to have one of three spinal conditions: Spinal Canal Stenosis, Neural Foraminal Narrowing, or Subarticular Stenosis. In addition to the condition, the data also specified which vertebral disk the condition was found at. The possible disks were L1, L2, L3, L4, or S1 with a severity level of Normal/Mild, Moderate, or Severe.

## Methodology
As this was my first attempt at building a CNN, my aim was to learn how to do it rather than achieve the highest score. I used Pytorch as my preferred deep learning framework and completed several machine learning tasks:

1. Converting the images to tensors
2. Image preprocessing and transformations
3. Loading the dataset into a dataloader
4. Defining the CNN architecture
5. Training and validating

## Reflections
This project was very rough around the edges as I had to learn many things from scratch, including lumbar spine diseases. However, I am very proud of having successfully trained the model I built from scratch. The knowledge gained here will definitely help future deep learning projects and has served as a great starting point. 


