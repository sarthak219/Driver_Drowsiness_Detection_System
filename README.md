# Driver Drowsiness Detection System using Deep Learning

## Introduction

Driver drowsiness has become a growing concern, especially among long-haul truck drivers who endure extended hours on the road without adequate rest. This not only jeopardizes their safety but also poses a risk to other road users. My Driver Drowsiness Detection System is designed to address this problem by leveraging a machine learning model capable of detecting when a driver is becoming drowsy. The system accomplishes this by monitoring the driver's eye behavior and sounding an alarm if it detects closed eyes for an extended duration.

## About

Drowsy driving is a significant safety issue that can result in accidents, injuries, and fatalities. My system uses machine learning and computer vision to tackle this problem head-on. It continuously analyzes a driver's facial features, specifically their eyes, to determine if they are becoming drowsy. When the system detects signs of drowsiness, it issues an audio alarm to alert the driver, helping to prevent potential accidents.

## Technologies Used

- Python
- OpenCV
- TensorFlow/Keras

## Dataset

I trained and tested my model using the [OACE (Open and Close Eyes) dataset](https://www.kaggle.com/datasets/muhammadhananasghar/oace-open-and-close-eyes-dataset), which comprises approximately 100,000 images of open and closed eyes. This diverse dataset allows my model to generalize well and accurately distinguish between open and closed eyes.

To access the dataset, please follow the provided link.

## Model

My system employs a Deep Convolutional Neural Network (CNN) to classify images of eyes as either open or closed. The model architecture consists of multiple layers, including convolutional and pooling layers, which are optimized to extract meaningful features from the eye images. I also utilize the Haarcascade model to extract faces and eyes from camera frames.

For detailed information on the model architecture and training process, refer to my code repository.

## Usage

To use my Driver Drowsiness Detection System, follow these steps:

1. Install the required dependencies (Python, OpenCV, TensorFlow/Keras).

2. Clone my repository and navigate to the project directory.

3. Run the main.py file.

4. Give access to use your device camera.

4. The system will continuously monitor the driver's eyes and sound an alarm if drowsiness is detected.

## Performance

My Neural Network has been trained for 7 epochs, achieving remarkable performance metrics:

- Accuracy: 99.61%
- Precision: 99.84%
- Recall: 99.41%

These high-performance metrics demonstrate the effectiveness of my system in accurately detecting drowsiness.