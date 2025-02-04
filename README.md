🚧 Crack Detection Project 🏗️
Welcome to the Crack Detection Project, where we dive into using deep learning techniques to detect cracks in concrete surfaces. This project is split into several hands-on labs, guiding you through data preparation, model building, and evaluation.

📋 Labs Overview
🔍 Lab 1: Data Preparation
In this lab, we kicked things off by working with the Concrete Crack Images dataset. We learned how to:

📦 Download and organize the dataset.
🗂️ List file paths for cracked (positive) and non-cracked (negative) images.
🖼️ Visualize sample images to get a feel for the data.
This helped us understand the dataset’s structure, setting the stage for model development.

⚡ Lab 2: Data Preparation with PyTorch
In this lab, we leveled up by preparing the data using PyTorch. Key steps included:

🏷️ Assigning labels to images (1 = cracked, 0 = non-cracked).
✂️ Splitting data into training and validation sets.
🗃️ Creating a custom Dataset class to manage image data efficiently.
👀 Visualizing sample images from both training and validation datasets.
This lab was all about getting the data ready for model training in PyTorch.

🤖 Lab 3: Building a Classifier with ResNet50
Here, we dove into transfer learning by using the pre-trained ResNet50 model. We covered:

🚀 Importing libraries like Keras and ResNet50 for model building.
📥 Downloading the dataset and organizing it for training and validation.
⚙️ Defining global constants (batch size, image dimensions, etc.).
🔄 Setting up ImageDataGenerator for data preprocessing and augmentation.
📊 Preparing training and validation data generators to feed into the model.
This lab helped us build a powerful image classifier without starting from scratch!
