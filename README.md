Crack Detection Project
This project focuses on detecting cracks in concrete surfaces using image classification techniques. The workflow is divided into multiple labs, each addressing a critical step in the data preparation and model development pipeline.

Lab 1: Data Preparation
In this lab, we focused on downloading and preprocessing the Concrete Crack Images dataset. The key tasks included:

Importing necessary libraries and auxiliary functions.
Downloading the dataset and examining its structure.
Listing image file paths for both positive (cracked) and negative (non-cracked) samples.
Displaying and analyzing sample images to understand the dataset.
Lab 2: Data Preparation with PyTorch
This lab involved creating a dataset object using PyTorch. We covered:

Assigning labels to the images (1 for cracked, 0 for non-cracked).
Splitting the dataset into training and validation sets.
Defining a custom Dataset class to manage image data efficiently.
Visualizing specific samples from both the training and validation datasets.
Lab 3: Building a Classifier with ResNet50
In this lab, we leveraged transfer learning by using the pre-trained ResNet50 model for image classification. Key steps included:

Importing necessary libraries, including Keras and ResNet50.
Downloading and organizing the dataset for training and validation.
Defining global constants like batch size and image dimensions.
Using ImageDataGenerator for data augmentation and preprocessing.
