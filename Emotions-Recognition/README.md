# Facial Emotion Recognition with Convolutional Neural Networks

This repository contains code for building a Convolutional Neural Network (CNN) model to recognize facial emotions. The model is trained to classify facial expressions into one of the following emotions: Anger, Contempt, Disgust, Fear, Happy, Neutral, Sad, and Surprised.

## Dataset

The dataset used for training and testing the model. It consists of grayscale images of facial expressions categorized into different emotions. The dataset can be found [here](https://www.kaggle.com/datasets/tapakah68/facial-emotion-recognition).

## Requirements

To run the code in this repository, you need the following dependencies:
- Python 3
- NumPy
- pandas
- OpenCV (cv2)
- scikit-learn
- TensorFlow
- Matplotlib

You can install these dependencies using pip:
pip install numpy pandas opencv-python scikit-learn tensorflow matplotlib


## Usage

1. Clone this repository to your local machine
2. Navigate to the cloned repository
3. Run the `facial_emotion_recognition.ipynb` notebook in your preferred Python environment (e.g., Jupyter Notebook, Google Colab).
4. Follow the instructions provided in the notebook to execute the code cells sequentially.

## Model Training

The `facial_emotion_recognition.ipynb` notebook contains code for the following steps:
- Loading and preprocessing the FER2013 dataset
- Splitting the dataset into training and testing sets
- Defining a CNN model architecture for emotion recognition
- Compiling the model with appropriate optimizer and loss function
- Training the model on the training set
- Evaluating the model's performance on the test set
- Saving the trained model to a file (`emotion_detection_model_1.h5`)

## Making Predictions

After training the model, you can use it to make predictions on new images. The `predict_emotion.py` script demonstrates how to load the saved model and make predictions on an input image.

To make predictions on your own images, follow these steps:
- Provide the path to the input image in the `input_img_path` variable.
- Run the `predict_emotion.py` script.







