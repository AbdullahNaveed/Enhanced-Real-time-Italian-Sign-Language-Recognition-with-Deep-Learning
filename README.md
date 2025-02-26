# Enhanced-Real-time-Italian-Sign-Language-Recognition-with-Deep-Learning

## Project Overview

-This project enhanced the dataset described in the paper:
*Real-Time Italian Sign Language Recognition with Deep Learning* by R. G. et al. (https://ceur-ws.org/Vol-3078/paper-17.pdf)

In this work, the dataset was enhanced for real-world applications by introducing more varied backgrounds. The original images, which had a uniform black background, were augmented by isolating hand contours and compositing them onto multiple, diverse backgrounds.

## Key Components

- **Data Preprocessing & Augmentation:**  
  Techniques for isolating hand regions and compositing them onto various backgrounds to enrich the dataset and simulate real-world conditions.

- **Custom CNN Model Training:**  
  A custom CNN architecture consisting of five convolutional blocks and fully connected layers was trained on the augmented dataset.
  
- **Real-Time Sign Language Interpreter:**  
  Code for capturing a region of interest from a webcam feed and performing real-time sign language recognition.

- **ResNet18 Experiment:**  
  An additional experiment where a ResNet18 model was trained on the same augmented dataset to compare performance.


## Usage

- **Data Preprocessing:**  
  Run `Data Preprocessing and Augmentation.ipynb` to process and augment the dataset.
- **Model Training:**  
  Run `CNN Model.ipynb` to train the custom CNN model.
- **ResNet18 Experiment:**  
  Run `RESNET18.ipynb` to train the ResNet18 model.
- **Real-Time Recognition:**  
  Run `Italian Sign Language Interpreter.ipynb` to start the webcam-based, real-time sign language recognition.

## Results

Detailed results and analysis are provided in the project report (`Report.pdf`).
