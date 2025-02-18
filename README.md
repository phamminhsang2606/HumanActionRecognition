# Human action recognition model using CNN + LSTM convolutional network
## Human Action Recognition

This repository contains code for human action recognition using deep learning models.

## Introduction

The human action recognition model included in this repository is based on a Long Short-Term Memory (LSTM) neural network architecture. It is trained to classify various human actions from video data. The model takes sequential frames of a video as input and predicts the action performed in the video.

## Model Details

The LSTM model architecture consists of multiple LSTM layers followed by fully connected layers. It was trained on a dataset comprising several action categories, including:
Archery
Biking
Horse riding
Walking with a dog
Body weight squats
Bowling
Boxing (punching bag)
Diving
Drumming
Golf swing

## Usage

To use the model for action recognition:
- Upload a video file or an image.
- Utilize the provided Python script `ActionCode.py`.
- Follow the instructions provided in the script to predict actions in videos or images.
## User interface
Build an interface with pyQt5 for action recognition
![image](https://github.com/Sangqpham0102/HumanActionRecognition/assets/119334855/12b6a813-6dde-448c-88d3-894d4b02cd17)
## Video Demo
[Watch the demo video](https://github.com/Sangqpham0102/HumanActionRecognition/blob/main/output.avi)
## Image demo
![image](https://github.com/Sangqpham0102/HumanActionRecognition/assets/119334855/852d950b-2ad7-4c39-a292-e5f9e0b8ab48)
![image](https://github.com/Sangqpham0102/HumanActionRecognition/assets/119334855/7fe8ffe6-a342-4857-9f4e-68bd67a6716a)


## Requirements

To run the code, you need the following dependencies:
- Python 3
- OpenCV
- TensorFlow/Keras

## Contribution

Feel free to contribute to this repository by adding improvements or expanding the dataset for better model performance. Pull requests are welcome!

## License

This project is licensed under the [MIT License](LICENSE).
