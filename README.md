This repository contains code for detecting violence scenes in motion pictures using Convolutional Neural Networks (CNNs). The goal of this project is to develop a model that can accurately identify violent scenes in videos, which can be useful for content moderation, parental controls, and other applications.

Dataset

The dataset used for training and testing the model is not included in this repository due to its size and licensing restrictions. However, you can obtain similar datasets from various sources such as academic repositories or by collecting your own dataset.

Requirements

Python 3
TensorFlow
Keras
OpenCV
NumPy
Matplotlib

Install the dependencies using the following command:


bash
Copy code
pip install -r requirements.txt
Usage

Data Preparation: Organize your dataset into two folders: violence and non_violence, containing videos labeled accordingly.

Data Preprocessing: Preprocess the videos to extract frames and generate training data.

Model Training: Train the CNN model using the preprocessed data.

Model Evaluation: Evaluate the trained model's performance on a separate test set.

Inference: Use the trained model to detect violence scenes in new videos.

Code Structure
data_preparation.py: Script for preprocessing the video data.
model.py: Defines the CNN architecture.
train.py: Script for training the model.
evaluate.py: Script for evaluating the model.
inference.py: Script for performing inference on new videos.
utils.py: Utility functions.
Contributing
Contributions are welcome! If you have any suggestions, enhancements, or bug fixes, feel free to open an issue or create a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
This project was inspired by the work of [cite relevant papers or projects here].
Special thanks to [mention any contributors or resources here].




# NAAN-MUDHALVAN
PROJECT SUBMISSION
