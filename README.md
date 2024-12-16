# Tomatoe_Image_Classification
This repository contains a machine learning pipeline for classifying tomatoes as Ripe or Unripe using Convolutional Neural Networks (CNNs). The project is built in Python and leverages TensorFlow/Keras for model training and evaluation.

### Data Preparation

- Images were collected from the internet and loaded from the directory, with invalid files being discarded.
- Data is split into training, validation, and test datasets.
- Image augmentation and normalization are applied for better generalization.

### Model Architecture

A CNN model is built with three convolutional layers, max pooling, and dense layers.
The model outputs a binary classification (Ripe/Unripe).
Training and Evaluation

The model is trained on the preprocessed data with a 70-20-10 split for train, validation, and test sets.
Metrics such as accuracy, precision, and recall are calculated.
Visualization
![1000_F_289904951_uGunB0aJjaVjV1sXhEkzoqKPzQMpqgjb](https://github.com/user-attachments/assets/2728795f-71bd-49fc-bf79-0354330b7087)

Performance metrics (loss and accuracy) are visualized.
The confusion matrix is plotted to assess classification performance.
Prediction

The trained model predicts the class of new images.
Input images are resized and normalized before prediction.
