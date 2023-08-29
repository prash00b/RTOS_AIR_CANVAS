# RTOS_AirCanvas
## An Air draw shapes prediction application


Real Time Object Tracking and Shape Description Using Aircanvas is a computer-vision neural network project that helps you draw in the air and use the trained CNN (Convolution Neural Network) model to recognise the shapes drawn.



## Features
- Draw on the canvas using different colors and an eraser.
- Object tracking based on color.
- Shape prediction from an image.
- Clear the canvas.
- Toggle drawing mode.

## Prerequisites

It uses a number of open source projects to work properly:

- [Python] - A versatile programming language used for building applications
- [Camera] - Either a phone camera or a webcam for capturing video.
- [OpenCV] -An open-source computer vision library that will be used for object detection and tracking
- [TensorFlow]- An open-source machine learning framework used for neural network operations.
- [TensorFlow Hub] A repository of pre-trained machine learning models and modules.
- [PIL (Python Imaging Library)]Used for image manipulation and processing tasks.
- [keras] A high-level neural networks API, running on top of TensorFlow.


## Installation

1. Clone the repository: `git clone git@github.com:prash00b/EPL-matchprediction.git`
2. Navigate to the project directory:
3. Install dependencies: `pip install numpy
pip install opencv-python
pip install cvzone
pip install tensorflow`


## Usage

1. Run the script: `python interactive_drawing.py`
2. Press 'd' to toggle drawing mode (on/off).
3. Press 'p' to predict shapes from the canvas.
4. Press 'q' to quit the application.
   
## How it Works

The program OpenCV to capture webcam input and display the interactive canvas. The canvas supports drawing, object tracking, and shape prediction. Press 'd' to enable drawing mode, and 'p' to predict shapes from the current canvas.
