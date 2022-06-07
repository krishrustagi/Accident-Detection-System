# Accident Detection System

**Last Updated: *7 June 2022***

1. What is Accident Detection System?
2. Prerequisites
3. Getting Started- How to use it?
4. Description
5. Future Work

## 1. What is Accident Detection System?

An accident Detection System is designed to detect accidents via video or CCTV footage. Road accidents are a significant problem for the whole world. Many people lose their lives in road accidents. We can minimize this issue by using CCTV accident detection. This repository majorly explores how CCTV can detect these accidents with the help of Deep Learning.

## 2. Prerequisites

- To use this project Python Version > 3.6 is recommended.
- To contribute to this project, knowledge of basic python scripting, Machine Learning, and Deep Learning will help.

## 3. Getting Started - How to use it?

### Clone this repository

`https://github.com/krishrustagi/Automatic_Attendance_System.git`

To install all the packages required to run this python program
`pip install -r requirements.txt`

**Note:** This project requires a camera. So make sure you have a connected camera to your device. You can also use a downloaded video if not using a camera.

### Run

To run this python program, you need to execute the `camera.py` python file.

## 4. Description

This program includes 4 things.

1. `data`: Kaggle dataset on [Accident Detection from CCTV footage](https://www.kaggle.com/code/mrcruise/accident-classification/data).
2. `accident-classification.ipynb`: This is a jupyter notebook that generates a model to classify the above data. This file generates two important files `model.json` and `model_weights.h5`.
3. `detection.py`: This file loads the Accident Detection system with the help of model.json and model_weights.h5 files.
4. `camera.py`: It packs the camera and executes the `detection.py` file on the video dividing it frame by frame and displaying the percentage of the prediction in the accident (if present) in the frame.
