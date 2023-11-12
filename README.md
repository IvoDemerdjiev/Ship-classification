Ship Classification using Deep Learning

This repository contains a deep learning project that focuses on classifying images of ships into different categories, such as Cargo, Military, Carrier, Cruise, and Tankers. The project uses TensorFlow and EfficientNetB3 as the base model for image classification.

Dataset
The dataset consists of ship images and corresponding labels. The images are categorized into one of the five classes. The dataset is divided into a training set and a test set, which is used to evaluate the model's performance.

Data Preprocessing
The code provides various data preprocessing steps, such as analyzing image color distribution, checking for grayscale images, and extracting features like HOG and SIFT. These steps help ensure that the data is suitable for training.

Data Augmentation
Data augmentation is a crucial part of the deep learning pipeline. The code includes data augmentation techniques to increase the diversity of the training dataset, enhancing the model's ability to generalize. Augmentation methods like horizontal flip, rotation, and zoom are applied to the images.

Model Architecture
The core of this project is the deep learning model used for ship classification. The code employs EfficientNetB3 as the base model and fine-tunes it to the ship classification task. The model is designed to predict the ship's category based on the input image.

Training
The code includes a custom callback called LRA (Learning Rate Adjuster), which dynamically adjusts the learning rate during training based on the model's performance. The callback monitors various metrics, such as training accuracy and validation loss, to make these adjustments. It also has the ability to pause training and ask the user for instructions.

Usage
To run this code, you need to have TensorFlow installed. The dataset should be organized with ship images in a directory, and the labels provided in a CSV file. You can configure the training parameters and model settings as needed.

Results
The README includes details about the training process, including the number of epochs, learning rate adjustments, and model performance. Visualizations, such as training curves and augmented images, can be added to showcase the results.

Conclusion
This project serves as a practical example of using deep learning for image classification tasks. By fine-tuning a pre-trained model and implementing data augmentation and dynamic learning rate adjustment, it achieves a high level of accuracy in classifying ships into different categories.

Feel free to explore the code and customize it for your own image classification tasks!
